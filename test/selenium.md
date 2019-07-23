## Selenium

### WebDriver Wait

Always avoid using __Thread.sleep(...)__

##### Implicit wait
This means that we can tell Selenium that we would like it to wait for a certain amount of time before throwing an exception that it cannot find the element on the page.

##### Fluent wait
Each FluentWait instance defines the maximum amount of time to wait for a condition, as well as the frequency with which to check the condition. Furthermore, the user may configure the wait to ignore specific types of exceptions whilst waiting, such as NoSuchElementExceptions when searching for an element on the page

`Wait wait = new FluentWait(driver).withTimeout(30, SECONDS).pollingEvery(5, SECONDS).ignoring(NoSuchElementException.class);
  WebElement foo = wait.until(new Function() {
    public WebElement apply(WebDriver driver) {
    return driver.findElement(By.id("foo"));
  }`

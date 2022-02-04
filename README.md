# Karate Snippets for VSCode

This extension adds snippets for Karate DSL.\
Helps writing tests easy and fast, as there is no intellisense with Karate.

## Features

- Support for most used Karate Core (UI) actions

\!\[feature X\]\(images/feature-x.png\)

## Snippets

|                 Prefix | Example                                                      |
| ---------------------: | ------------------------------------------------------------ |
|              `kclear→` | `clear("locator")`                                           |
|              `kclick→` | `click("locator")`                                           |
|       `kdeleteCookie→` | `deleteCookie("cookieName")`                                 |
|          `kdriverUrl→` | `driver "url"`                                               |
|              `kfocus→` | `focus("locator")`                                           |
|              `kinput→` | `input("locator", "string")`                                 |
|     `kmatchAttribute→` | `match attribute("locator", "attribute") == "expectedValue"` |
|       `kmatchEnabled→` | `match enabled("locator") == true`                           |
|          `kmatchText→` | `match text("locator") contains "expectedText"`              |
|         `kmatchValue→` | `match value("locator") == "expectedValue"`                  |
|        `kmatchExists→` | `match exists("locator") == false`                           |
|           `ksetValue→` | `value("locator", "value")`                                  |
|             `kscroll→` | `scroll("locator")`                                          |
|        `kscrollClick→` | `scroll("locator").click()`                                  |
|        `kscrollInput→` | `scroll("locator").input("text")`                            |
|        `kselectLabel→` | `select("locator", "{}label")`                               |
|        `kselectValue→` | `select("locator", "value")`                                 |
|        `kselectIndex→` | `select("locator", index)`                                   |
|            `kwaitFor→` | `waitFor("locator")`                                         |
|     `kwaitForEnabled→` | `waitForEnabled("locator")`                                  |
|         `kwaitForUrl→` | `waitForUrl("url")`                                          |
|        `kwaitForText→` | `waitForText("locator", "expectedText")`                     |
| `kwaitForResultCount→` | `waitForResultCount("locator", amount)`                      |

*** Settings ***
Library               Selenium2Library

*** Test Cases ***
Hello
    Open Browser      http://www.google.com
    Close Browser

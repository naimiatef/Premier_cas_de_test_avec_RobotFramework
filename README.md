# Premier_cas_de_test_avec_RobotFramework


*** Settings *** <br>
Library    SeleniumLibrary
*** Test Cases ***
premier test
    log    Hello world
TC1
    open browser    https://naimiatef.systeme.io/test-logiciel    Chrome
    maximize browser window
    sleep    5s

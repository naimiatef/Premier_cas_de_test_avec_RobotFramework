# Premier_cas_de_test_avec_RobotFramework


*** Settings *** <br>
Library    SeleniumLibrary<br>
*** Test Cases ***<br>
premier test<br>
    log    Hello world<br>
TC1<br>
    open browser    https://naimiatef.systeme.io/test-logiciel    Chrome<br>
    maximize browser window<br>
    sleep    5s

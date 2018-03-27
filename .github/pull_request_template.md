This pull request is part of the work described in [CARS-XXXX](https://naspersclassifieds.atlassian.net/browse/CARS-XXXX) (epic or issue?) required to make Something (another link to task?) work in the backend/frontend part.

**To achieve this, we:**

1. Added JohnDoeClass to the services.php
2. Use JohnDoe service in JaneDoeController to do something
3. Refactored someMethod() to have just one responsibility to do Something and created anotherMethod() to be responsible do the other thing

### Dependencies:
Depends on [#XXXX](https://github.com/naspersclassifieds-regional/verticals-cars-atlas-web-dist/pull/XXXX) pull request.

### Requirements:
1. Before deploy in production, run [file-description-01.sql](https://naspersclassifieds.atlassian.net/secure/attachment/XXXX/file-description-01.sql) to create parameters in the *otomoto* database
2. After deploy in production, execute the HelloWorldScript command in production:
`atlas exec otomotopl run naspersclassifieds:regional:verticals:cars:atlas:web:lib:console:OneTimeExecution:HelloWorldScript --showLogs --message='hello world!'`

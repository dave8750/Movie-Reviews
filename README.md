# Movie-Reviews-progress

!!!!IMPORTANT!!!!

ak nejde zbehnut program a vyskytuju sa problemy, je mozne ,ze nie su nainstalovane frameworky cez NuGet/treba updatnut migraciu
Ak hej, treba zadat tieto nasledovne commandy do NuGet Mannager Console 

Install-Package Microsoft.EntityFrameworkCore

Install-Package Microsoft.EntityFrameworkCore.SqlServer

Install-Package Microsoft.EntityFrameworkCore.Tools

Update-Database -Context UserDbContext

Update-Database -Context MovieDbContext


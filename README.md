# Foreign keys in the MODX schema

The goal of this project is to _visualise_ schema relations in MODX. After a fruitless afternoon trying to navigate from one side of the ACL to another, I decided it was time to do this.

## Outcomes

1. A nice visual diagram showing the relations between models
2. A SQL schema using InnoDB tables with foreign keys (and using `ON DELETE SET NULL` so no unexpected side effects from cascades)

## How you can contribute
The work is being done using the free [MySQL Workbench](http://dev.mysql.com/downloads/workbench/). To contribute, [download](http://dev.mysql.com/downloads/workbench/) and install it, open `document.mwb.xml` in Workbench and make your edits.

The MODX schema XML file is included for your convenience, so you can refer to it for relationship information.

**Note:** Normally you edit a `.mwb` file with Workbench. This is a zip file which contains a small database, the `document.mwb.xml` and a lock file. Because a zip is a binary file, it's not easy to keep under source control. For our purposes, editing the XML file directly works.
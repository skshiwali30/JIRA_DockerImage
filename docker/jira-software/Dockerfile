FROM atlassian/jira-software:latest

COPY --chown=jira:jira dbconfig.xml /var/atlassian/application-data/jira/dbconfig.xml

COPY --chown=jira:jira h2db.mv.db /var/atlassian/application-data/jira/database/h2db.mv.db
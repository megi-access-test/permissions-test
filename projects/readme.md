### sample project.yml
This is the starting point for data_guru-api. Members modified here are modified accordingly in the integration files, which are created with the names given here. Integration files are the ones in `github_teams/`, `google_groups/projects/`, `rollbar_teams/`, `toggl_teams/client_projects/`.  
  
_Sidenote_: For Slack channel names, prefixes `client-` and `project-` accordingly are mandatory.  
  
Keys and values must be ordered a-z.
```
---
description: Whereabouts and stuff                # optional
display_name: Project Name                        # required
github_teams:                                     # required
- first_team
- other_team
google_groups:                                    # required
- first-team                                      
- other-team
jira_project_name: PN board                       # optional
members:                                          # required
- first.member.name
- other.member.name
people_project_name: project_name                 # required
pivotal_project_name: Project Name                # optional
project_email: project-name@netguru.pl            # required
rollbar_teams:                                    # required
- first_team
- other_team
slack_client_channel_name: client-project_name    # optional
slack_project_channel_name: project-project_name  # required
toggl_teams:                                      # required
- first_team
- other_team
```

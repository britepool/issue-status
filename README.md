# Issue Status

Issue Status is the static client-side status page built on React using GitHub Issues for Component and Incident reporting with live updating using the GitHub API, there is no need to rebuild and redeploy for every update. All hosted on GitHub Pages

You can view the BritePool status page here: [Status Page](https://britepool.github.io/issue-status/)
You can view the original forked README page here: [ORIGINAL.md](./ORIGINAL.md)

![Banner](/banner.gif?raw=true)

# Tracking Incidents

## Creating a new incident
To create a new incident, [CLICK HERE](https://github.com/britepool/issue-status/issues/new?assignees=&labels=incident%2C+issue+status&template=new-incident.md&title=Summarize+the+incident)

Fill out
* Incident summary as issue title
* Any uncommented text in the issue description will be displayed below the incident

After creating your incident, please update any affected components with their status, the applicable labels are:
* operational
* performance issues
* partial outage
* major outage

## Updating an incident

* Any uncommented text in the issue description will be displayed below the incident, you can edit this over time to update the status of the incident
* Any important information can be added as comments to the issue itself, e.g. resolution, etc. and will not be displayed on the status page

## Closing an incident

* Simply mark the issue as Closed and it will be reported as closed on the status page

After closing your incident, please update any affected components with the `operational` status label and remove any of the others previously selected
* performance issues
* partial outage
* major outage

# Adding major components

To create a new component, [CLICK HERE](https://github.com/britepool/issue-status/issues/new?assignees=&labels=component%2C+issue+status%2C+operational&template=new-component.md&title=)

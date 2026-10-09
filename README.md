# jenkins-practical
A scheduled build is a Jenkins job that runs automatically at a specific time or interval.
Yes. When the scheduled job runs, Jenkins can check GitHub for changes.
There is nothing new to build. Jenkins may report that there are no changes.
A webhook is a message sent from GitHub to Jenkins when an event happens, such as a push.
A GitHub event, usually a push to the repository, causes the build.

Scheduled build: triggered by time.

Webhook: triggered by a GitHub event.

Scheduled builds may wait several minutes.

Webhooks can trigger almost immediately after a push.


Scheduled build: Running a build every 10 minutes to regularly check a project.

Webhook: Automatically building the project immediately whenever a developer pushes new code to GitHub.


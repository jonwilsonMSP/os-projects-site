# Steps to a Minimum Viable Project

- Users need to be able to submit ideas, or current projects
- Users should be able to post, or submit, links to works-in-progress
- Each idea or project needs to have basic info: a title, a brief description, whether or not it's already in-progress, and if so, a link to its repo
- The home page should have a simple list view of all current projects, with the appropriate info and links
- Info about how to start a project based on an idea, and post (or submit) a link to it
- (Maybe) A link to my (or somebody else's, if a good one exists) open source skeleton
- Need to decide whether idea submissions will be owned by their submitters, if so, they should not be deletable after someone has started and linked a project
- Projects, and if applicable, their pages should be owned by individual users
- If projects have a link to a working demo, in addition to a repo, that link should appear either on the list view, or on the project's page ( only if every project, by default, has its own page)
- Need to decide whether users need to have profile pages for the MVP
- If voting is allowed, need to decide how to permit voting--users only? is there a way to verify users, or to semi-verify, maybe through a connected app, like Github?
- (Maybe) Each project can have a dedicated page, with more details
- (Maybe) For works-in-progress, maybe allow thumbnails to be attached to
- (Maybe) Allow users to vote for specific ideas, to push them closer to the top and make them easier to find
- (Maybe) There should probably be a way to link to more than one work-in-progress for a specific idea
- (Maybe) Allow users to vote for specific projects if an idea has more than one work-in-progress
- Allow submitting of proposed projects, to lower the bar for project submission, so the owner doesn't have to learn and go through all the steps of setting it up as an OS project; someone else who's interested in the project and has the know-how can set up a bare bones repo, and then either:
  1.  allow the owner to submit their project as a pull request, or
  2.  they could clone the project if the owner includes an OS license.
- At some point add tutorials:
  1.  How to submit a project or idea, what happens next, etc.
  2.  How to make your first contribution (pull request)--maybe link to this great video walk-through of making a PR on Github: https://www.youtube.com/watch?v=YTbRzhQju4c
- Add "Help wanted", tags and "Teams" features:
  1.  Each project owner should be able to tag items as "Help Wanted" on the project page, and
  2.  Also be able to add tags to "Help Wanted" items, like "Node.js", "React", "front end design", etc.
  3.  This would allow projects to form teams, where members could contribute specific skill sets
  4.  At some point, users should be able to have a profile page where they list skills ("OS specialist", "Node specialist", etc.)
- For web apps, the project can be open source, but if there are one or more sites based on the project, the site owner(s) will need to be responsible for Terms of Service and Privacy policies--is there a way to make this easier (maybe ask for contributors with security skill sets)?
  - Also, of course, no authentication secrets should ever be posted in any public repo--do users need to be reminded of this?
  - To what degree can the authentication work be done in the public repo, without compromising security--is it just the authentication secrets that need to be hidden? Should site owners be responsible for that whole workflow?
- Different categories of tags for projects:
  - Help wanted (tagged by type of help needed)
  - Type(s) of project
    - Type of stack
    - Type of problem being solved
    - Type of site (?)
  - Different stages in the process (not necessarily chronological)
    = idea proposed
    - discussion started
    - project launched
    - site or app running

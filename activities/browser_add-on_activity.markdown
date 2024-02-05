---
layout: activity
---

# Browser Add-on Activity

Note1: students work in groups of 3. The instructions indicate which parts of this activity should be performed
by all team-members and which should be performed by one team member.

Note2: students do not need to be familiar with Javascript in order to complete this activity


Prerequisites:
- Firefox should be installed on your system
- you should have Git installed on your system if it is not there already, <br>
  <details markdown="1">
  <summary markdown="1">see how </summary>
  <p markdown="1">

  For download and install instructions and for a list of available graphical interfaces
  see the [git-scm.com](https://git-scm.com/downloads) site.

  </p>
  </details>
- you should have Git configured on your system to _know who you are_,
  <details><summary>see how </summary>
  <p>
  Run the following commands from the command line:<br>

  ```
  git config --global user.email "YOUR_EMAIL"
  git config --global user.name "YOUR NAME"
  ```
  (The email should be the same email you used to register your GitHub account. Your name should be your name or nickname      - just make sure that it is proper and recognizable since it will be associated with all of your commits.  It can be your GitHub username. ) <br>
  For example, <br>

  ```
  git config --global user.email "joannakl@cs.nyu.edu"
  git config --global user.name "JoannaKl"```<br>
  ```
  </p></details>


The Mozilla Developers Network has
a tutorial on [Browser Extensions](https://developer.mozilla.org/en-US/docs/Mozilla/Add-ons/WebExtensions) that
you will be using during this activity.

## Part 0: Setup your live-log

You should keep a Ed live-log during this activity.
- Create a post on Ed in the Add-on Activity category. The title of the post should follow given
template: Team-XXX Live Log, in which you replace the XXX with your team number. 
- List the members of the team in the body of the post. (Note, only one person is able to 
edit the post itself.)
- Log your progress as you complete different parts of the activity using Comment feature on the posts. 
(Note, that this is going to create a list of comments in reverse chronological order with the 
most recent comments on top.) 
- Do not duplicate the answers that you are providing elsewhere. There should be regular entries in the log.
You should no be just summarizing what you did at the very end. Everybody in your team can make comments. 

See a sample [live log](https://edstem.org/us/courses/54797/discussion/4271196) and make sure you create a similar live log to keep track of your group's progress. (The only difference is that the sample has time-stamps on comments that are too close together to be realistic.) 



## Part 1: Creating and installing your very first Firefox extension

- locate the _Your first extension_ link under the _Getting Started Section_ in the
[Browser Extensions](https://developer.mozilla.org/en-US/docs/Mozilla/Add-ons/WebExtensions) tutorial
- each student should follow the steps to create this very simple extension
(feel free to modify the color and/or the domain)  
- once finished, help out your other team members

When you are __all__ done, let the facilitator know by updating your live log.

## Part 2: Creating and installing a more sophisticated extension

- locate the _Your second extension_ link under the _Getting Started Section_ in the
[Browser Extensions](https://developer.mozilla.org/en-US/docs/Mozilla/Add-ons/WebExtensions) tutorial
- each student should follow the steps to create this very simple extension (feel free to modify the images used)
- once finished, help out your other team members

When you are __all__ done, let the facilitator know by updating your live log.

## Part 3: Repository exploration

When you were working on the previous part, you should have encountered references to the
[MDN WebExtension repository](https://github.com/mdn/webextensions-examples).
Go to that repository and locate the following files: LICENSE, README.md, CONTRIBUTING.md, and CODE_OF_CONDUCT.md.  Answer the questions below as a team. Your answers should be placed under heading
_Part 3_ in a file called
`team_NUMBER.md` (where `NUMBER` is replaced by your team number) in the repository called `add-on-activity` in the
course organization. Answer the questions below under the heading _Part 3_. 

1. What does this repo use the README.md file? What kind of information is included there?
1. What does this repo use the LICENSE file? Does it need to be in a repository?
1. What is the purpose of the CONTRIBUTING.md file? 
1. Describe one type of contribution to this repository that does not require writing any code.
1. What is the purpose of the CODE_OF_CONDUCT.md document?
1. Describe three types of behaviors that violate the Mozilla Community Participation Guidelines.
1. If a person working with the content of this repository runs into problems or has questions, what can they do?

When your group is done, let the facilitator know by updating your live log.

## Part 4: Explore existing extensions  

Go to [Firefox Add-ons](https://addons.mozilla.org/en-US/firefox/) page. As a team, decide on your _favorite_
extension. List the name and the link to that extension in your team's file in the `add-on-activity` repository
under the heading _Part 4_. Then answer the following questions about your chosen extension.

1. What is the homepage for the extension?
2. What is the license under which the extension is distributed?
3. Can you find a code repository for this extension?
4. Is the extension that you picked an open source project?
5. Can you find information about how many different users contribute to this project? If so, specify how many.
6. If the extension is an open source extension, is it open to contributions? If so, 
how did the mantainers communicate that fact? 

When your group is done, let the facilitator know by updating your live log.


## Part 5: Create your own

As a team, create an idea for an extension. It can be a very simple one, or a more complicated one (this idea can
evolve/change after today, so do not worry about having everything finalized).

- Create a repository in the class organization with the name of your extension (NOT the name of your team). In your team's file for `add-on-activity`
provide a link to that repository under heading _Part 5_.
- Create a README.md file with a description of the idea for your extension.
- Create other files that will make this an open soure project.

When your group is done, let the facilitator know by updating your live log.


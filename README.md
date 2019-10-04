<h1 align="center">Git Web Development</h1>
<img align="right" src="https://img.shields.io/badge/Lambda School Assignment-Git-RED?style=flat&logo=appveyor"/><br>
<i align="center">In this project you will be using the concepts learned in the Git for Web Development lesson to <code>fork</code>, <code>clone</code>, & <code>push</code> and submit a PR for each project during this sprint.</i>


<h2 align="center">🕵🏿‍Objectives🕵🏿‍</h2>
 <ul>
  <li>✅ | Create your own version of this repo with <code>fork.</code></li>
  <li>✅ | Add your TL as a collaborator.</li>
  <li>✅ | Clone this repo.</li>
  <li>✅ | Create a branch <code>git checkout -b 'firstName-lastName</code>.</li>
  <li>✅ | Add a file to the project called <code>{{ yourFirstName-yourLastName }}.txt</code>.</li>
  <li>✅ | Run your usual git commands for adding/commiting and pushing</li>
      <b><i>Be sure to push to your branch!</i></b>
  <li>✅ | Create a Pull-Request to submit your work.</li>
  <li>✅ | Use your own student fork as the base (compare across forks, base-fork -> master).</li>
  <li>✅ | Add your TL as a reviewer on the Pull-Request.</li>
     <i>TL then will count the Assignment as done by merging the HW back into master "STUDENT FORK".</i>
</ul>

<h2 align="center">🥅sTretCh gOalS🥅</h2>
<i align="center">While the processes learned here will set you up to be successful in most situations, they are just the tip of the iceberg in learning Git. Independantly research the following topics to learn more about Git.</i>

<h3>Questions ❓ ❓ ❓</h3>
<ol>
 <li>✅ | Research and understand what a <code>merge conflict</code> is and how to resolve it.
 <blockquote><i>a <b>merge conflict</b> means two conflicting commits are trying to merge into master and Git needs the user to decide which commit to send.<br>Easiest way to resolve os to choose the most updated commit and <code>re-stage, commit</code>, & <code>push</code>.</i></blockquote><br></li>

 <li>✅ | Reseach the Git commands <code>pull</code>, <code>rebase</code>, <code>merge</code>.
 <blockquote><i>These commands allow you to change the code base for everybody on your branch.<br>
  <ul>
   <li><code>pull</code>: <b>updates</b> local clone with latest commit from Git repo.</li>
   <li><code>rebase</code>: <b>rewrites</b> repo git history by restructuring got commits to new first commit.</li>
   <li><code>merge</code>: <b>combines</b> a branch checkouted frorm master back into <code>master</code>.</li>
  </ul></i></blockquote><br></li>

  <li>✅ | Reseach the Git commands <code>reset</code>, <code>revert</code>, & <code>clean</code>.<br><blockquote><i>These commands will allow you to go back and ammends previous commits you have made.
   <ul>
    <li><code>reset</code>: undoes all changes made in a partciular commit, or to an entire active directory. Requires the <code>-hard</code> option to work.<br>Use <code>git reset -hard {{ commit }}</code> OR <code> git reset -hard Head</code></li>
    <li><code>revert</code>: creates a new commit with none the changes of the selected commit.<br> Use <code> git revert {{ commit }}</code></li>
    <li><code>clean</code>: deletes all untracked files</code> by Git in a particular commit, the current active directory, or certain files with extensions <code>-e</code> in a filter option.<br> Use <code> git clean [ -d [[ regex_pattern ]]</code></li>
    </ul></i></blockquote></li>
   </ul><br></li>

  <li>✅ | Research and set up a Graphical User Interface (GUI) Git console.<br> 
   <blockquote><img src="git-gui.png"/></blockquote><br></li>

  <li>✅ | Research and setup SSH keys with Github, so that you do not need to input your username/password each time you push.
  <blockquote>SSH is an implementation of a rigourous <code>public / private key</code> encryption scheme that stands for <b>Secure Shell</b>. It's so robust, passwords and usernames are unnecceary. You and a server <i>(Github for instance)</i> share a generated known public key. Then, upon request, a <code>private</code> key can be generated based off the public key <i>(with an equation)</i> that is computationally impossible <a href="https://www.wired.com/story/googles-quantum-supremacy-isnt-end-encryption/"><i>(for now)</i></a> to reverse-engineer - like guessing which grain of sand on a beach is yours.</li> 
</ul>
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
</head>
<body>
    <h1>Git Version Control ReadMe</h1>
    <h2>Resources</h2>
    <ul>
        <li><a href="https://git-scm.com">Git</a></li>
        <li><a href="https://marklodato.github.io/visual-git-guide/index-en.html">Visual Git Guide</a></li>
        <li><a href="https://git-scm.com/book/en/v2">Pro Git Book (v2)</a></li>
        <li><a href="https://www.freecodecamp.org/news/learn-the-basics-of-git-and-github/">FreeCodeCamp: Git and GitHub for Beginners</a></li>
        <li><a href="https://www.javatpoint.com/git">JavaTpoint Git Tutorial</a></li>
    </ul>
    <h2>What is Git?</h2>
    <p>Git is a distributed version control system used for tracking changes in source code during software development. It is designed to handle everything from small to very large projects with speed and efficiency. Here are the key features and concepts of Git:</p>
    <h3>Version Control</h3>
    <p>Git keeps a record of every change made to the codebase, allowing developers to revert to previous states, compare changes over time, and collaborate more effectively.</p>
    <h3>Distributed System</h3>
    <p>Unlike centralized version control systems, Git allows each developer to have a full copy of the entire repository history on their local machine. This setup enables working offline and provides redundancy.</p>
    <h3>Branching and Merging</h3>
    <p>Git supports branching, where developers can create separate branches for new features or experiments without affecting the main codebase. Merging combines changes from different branches, facilitating parallel development and collaboration.</p>
    <h3>Snapshots, Not Differences</h3>
    <p>Instead of storing differences between file versions, Git stores snapshots of the entire repository at each commit. If files haven't changed, Git links to the previous identical file.</p>
    <h3>Efficient and Scalable</h3>
    <p>Git is optimized for performance, handling large codebases and long histories efficiently.</p>
    <h3>Collaboration and Workflow</h3>
    <p>Git enables collaboration through workflows like feature branching, pull requests, and continuous integration/deployment (CI/CD) pipelines.</p>
    <h3>Commit History</h3>
    <p>Each commit in Git is identified by a unique SHA-1 hash, ensuring the integrity and security of the commit history.</p>
    <h2>Test Your Knowledge</h2>
    <h3>What is the history of Git?</h3>
    <p>Git was created by Linus Torvalds in 2005 to support the development of the Linux kernel. It was designed as a distributed version control system to handle everything from small to very large projects with speed and efficiency.</p>
    <h3>Why do we need Git?</h3>
    <p>Git is essential for:</p>
    <ul>
        <li>Tracking changes in source code during software development.</li>
        <li>Collaborating with multiple developers.</li>
        <li>Keeping a history of project modifications.</li>
        <li>Branching and merging code for parallel development.</li>
    </ul>
    <h3>What is the difference between local, central, and distributed version control?</h3>
    <ul>
        <li><strong>Local Version Control</strong>: Tracks changes in files on the same machine.</li>
        <li><strong>Central Version Control</strong>: Uses a single central server to store all versions of files, with multiple clients accessing this server.</li>
        <li><strong>Distributed Version Control</strong>: Each client has a full copy of the repository, including its history, allowing for offline work and multiple backup points.</li>
    </ul>
    <h3>What is the Git architecture?</h3>
    <p>Git architecture consists of:</p>
    <ul>
        <li><strong>Working Directory</strong>: The files you are currently working on.</li>
        <li><strong>Staging Area</strong>: A space where you can format and review changes before committing them.</li>
        <li><strong>Repository</strong>: The place where Git permanently stores all versions of the project.</li>
    </ul>
    <h3>What is the staging area?</h3>
    <p>The staging area (or index) is an intermediate space where changes are listed before they are committed to the repository. It allows you to format and review changes before making them part of the project history.</p>
    <h3>What is SHA?</h3>
    <p>SHA (Secure Hash Algorithm) in Git refers to SHA-1, which is used to name and identify objects within the Git repository. Each object is identified by a unique SHA-1 hash.</p>
    <h3>What is a Git object?</h3>
    <p>Git objects are the fundamental entities in a Git repository. The four types of Git objects are:</p>
    <ul>
        <li><strong>Blob</strong>: Stores file data.</li>
        <li><strong>Tree</strong>: Stores directory structures and blob identifiers.</li>
        <li><strong>Commit</strong>: Stores information about changes and references to trees and parent commits.</li>
        <li><strong>Tag</strong>: Points to another Git object, typically a commit, to mark a specific point in the repository's history.</li>
    </ul>
    <h3>What is a Git tag?</h3>
    <p>A Git tag is a reference that points to a specific commit, often used to mark release points (e.g., v1.0, v2.0).</p>
    <h3>What is the difference between <code>git log</code> and <code>git reflog</code>?</h3>
    <ul>
        <li><code>git log</code>: Shows the commit history of the repository.</li>
        <li><code>git reflog</code>: Records updates to the tip of branches and other references in the local repository. It includes changes that are not necessarily part of the commit history.</li>
    </ul>
    <h3>What is the difference between <code>git pull</code> and <code>git fetch</code>?</h3>
    <ul>
        <li><code>git pull</code>: Fetches changes from a remote repository and immediately attempts to merge them into the current branch.</li>
        <li><code>git fetch</code>: Fetches changes from a remote repository but does not merge them. It allows you to review changes before integrating them into your branch.</li>
    </ul>
    <h3>What is the difference between <code>git merge</code> and <code>git rebase</code>?</h3>
    <ul>
        <li><code>git merge</code>: Combines multiple sequences of commits into one unified history. It creates a new commit for the merge.</li>
        <li><code>git rebase</code>: Reapplies commits on top of another base tip, resulting in a linear project history. It rewrites commit history and is useful for maintaining a clean and understandable project history.</li>
    </ul>
    <h2>Contact Me</h2>
    <p>If you have any questions or need further assistance, feel free to contact me at <a href="mailto:mahmoud.abdelaal.dev@gmail.com">mahmoud.abdelaal.dev@gmail.com</a>.</p>
</body>
</html>

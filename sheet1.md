<!--
    TO DO
    -make it prettier
    -better formatting to incorporate flags and examples
    -put in examples
    -add workflows for git
    -add in page links
-->


<h1>Cheat Sheets for Web Dev Foundation</h1>
<article>
    <div>
        <h2>Terminal</h2>
        <p><code>pwd</code>shows the current directory</p>
        <p><code>clear</code> clears the output of the terminal</p>
        <p><code>ls</code> shows the content of the current folder <code>-l</code> shows the long form and
            <code>-a</code> shows hidden files
        </p>
        <p><code>cd ..</code> changes the directory to the next higher level</p>
        <p><code>cd ~</code> will bring you back to your home folder</p>
        <p><code>mkdir [name]</code> creates a new folder</p>
        <p><code>touch [filename]</code> creates a new file, you can create multiple files by seperating the filenames
            with spaces</p>
        <p><code>echo "[message]" > [filename]</code> will send the message argument to the specified file</p>
        <p><code>cat [filename]</code> shows the content of a file</p>
        <p><code> cat [filename1] > [filename2]</code> sends the contents of file1 to file2</p>
        <p><code>mv [filename] [foldername]</code> moves a file to specified folder</p>
        <p><code>mv [oldname] [newname]</code> renames a file</p>
        <p><code>cp [filename] [foldername]</code> copies a file to the specified folder</p>
        <p><code>code .</code> will open your IDE with all files in the folder</p>
        <p><code>which</code> shows from which folder a command is executed</p>
    </div>
    <div>
        <h2>Git</h2>
        <p><code>git config --global --list</code> will show the config of your current user</p>
        <p><code>git init</code>reates a empty Git repository in the current folder (be careful not to nest them)</p>
        <p><code>git status</code>shows information about the status of your repository</p>
        <p><code>git add [filename]</code> adds the file to the stage</p>
        <p><code>git add *.[filetype]</code> adds all files of the specified type to the stage</p>
        <p><code>git add *</code> adds all changed files to the stage</p>
        <p><code>git commit -m "[message]"</code> commits the changes to the current branch and a message (without
            opening an text editor)</p>
        <p><code>git log</code> shows a history of the current repository</p>
        <p><code>git remote add origin git@github.com:userName/repo.git</code> connects the local repository with a
            remote repository on github</p>
        <p><code>git remote -v </code> shows information about the remote status in long form</p>
        <p><code>git push -u origin main</code> connects the local branch with the remote main branch</p>
        <p><code>git push</code> will push your local commits to the remote repository</p>
    </div>
    <div>
        <h2>HTML</h2>
    </div>
</article>
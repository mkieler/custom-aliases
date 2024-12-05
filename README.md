## INSTALLATION GUIDE LINUX
Clone the repository to home folder

<ol>
    <li>Clone or download the repository to home folder </li>
    <li>Run this in terminal
        ```
            nano ~/.bashrc
        ```
    </li>
    <li> Add this to the bashrc file
        ```
        if [ -f ~/custom-aliases ]; then
            . ~/custom-aliases
        fi
        ```
    </li>
    <li> Apply changes immediately. Run this from terminal
        ```
        source ~/.bashrc
        ```
    </li>
</ol>









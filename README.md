
# Linux CLI Commands

- `cd -`    // Moved to last working directory
- `ls -R`   **ls -R / > terminal_text.txt**
- `rm -rf`  // remove all files in a directory
- `cat abc.txt > abc-copy.txt`  //create and copy file content
- `cat content.txt | [more,less]`
- `cat [filename] | grep [search word] > [filename]`
- `cat $(pwd)/[file-name]`      // [$(pwd)->short way of writing long path]
- `sed 's/[searching string]/[replacing string]/[g=global]' [filename]`
- `grep -i [type word] [filename]`
- `grep pi* [filename]`
- `top`
- `ps`
- `ps -aux`
- `elinks https://www.google.com/ &`    // [run this process in bg]
- `jobs`
- `fg [job number]`
- `bg`
- `kill -9 [PSID]`      // [kill process forcefully]
- `free -h`
- `cut -b [1-3,1,3] [text_filname]`
- `df -hT -x tmpfs`
- `ln -s [source-file-with-complete-path] [destination-soft-link-file-name]`
- `dd`
- `diff`
- `wc`
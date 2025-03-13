# Linux-Management-



##  Assisgnment 1:
-------------
### This is my very first assisgnment for the linux where i had linked my amk gmail id with the git and i had already created the  repository and i will summit my assisgnment here

## Assisgnment 2:
---------

##### In this case we need to  Select five level 2 directories and save their contents in one file, "listing.md". Here "level 2" directory is for example /home/mylogin/, but not /tmp/ (level 1) or /usr/local/bin/ (level 3). Contents = listing of filenames.

**At the begaining we need to put this code under our computer top get the level 2 disctionary at once**
 ```
 find / -mindepth 2 -maxdepth 2 -type d 2>/dev/null | head -n 5 | while read dir; do
  echo "Contents of $dir:" >> listing.md
  ls -1 "$dir" >> listing.md 2>/dev/null
  echo "" >> listing.md
done
```

### To verify the output we need to run the following command 
```
cat listing.md
```
### 2. Verify if the file exists and is not empty
```
ls -l listing.md

```
output 
-------------
![alt text](<Screenshot 2025-03-13 231951.png>) 
![alt text](<Screenshot 2025-03-13 231926.png>)

## content of files are in Screenshot

**you can acess it nby my git link i will add below to**

- https://github.com/aaysuhdr/Linux-Management-/blob/main/README.md 

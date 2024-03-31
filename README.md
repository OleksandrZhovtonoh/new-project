# Instuction

1. Install git on your machine
For MacOS:
```brew install git```
For Debian/Ubuntu
```sudo apt install -y git```

2. Initilize public git repository
In root directory type:
```git init``` 
```git remote add origin <your repo link> ```

3. Create new branch named as "development" (you will be automatically checked out in the "development" branch)
```git checkout -b main```
```git checkout -b development```

4. Create or change anything in the directory.

5. Add new changes to your repository
```git add .```

6. Commit your changes:
```git commit -m "Adding README.md"```

7. Merge you changes to the main branch "master"
```git checkout master```
```git merge development```

7. Push your changes to GitHub.com
```git push origin```

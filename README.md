# Youtube-data-Analytics
The file size was greater than 25 mb, LFS has helped a lot in uploading the file .You can download the file on your local by installing git lfs install.
The steps for uploading the large file size are:
pip install virtualenv
virtualenv lfs
source lfs/bin/activate
git lfs install
git lfs track "*.csv" 
git add .gitattributes
git init
ls
git remote add origin https://github.com/akshita2404/Youtube-data-Analytics
git remote -v
git add comments_all.csv
git commit -m "comments"
git push origin master

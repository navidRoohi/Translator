# Translator
Translator App


This project has written and modified based on Derek Banas page, for more information please have a look at : 
https://www.youtube.com/watch?v=Z149x12sXsw

If some of you have any trouble with missing libraries (Cannot resolve token) on classes like DefaultHttpConnection, follow this simple steps:
1. Go to File -> Project Structure.
2. Under Modules click on 'app' and than change to the dependencies folder.
3. Click on the green plus sign in the upper left area of the window.
4. Select Library Dependency
5. Write in the search box "org.apache.http" and hit Enter (or search).
6. Select the one starting with org.jbundle.util.osgi.wrapped.
7. Click Ok and Ok again to close the window. Your project should now refersh.



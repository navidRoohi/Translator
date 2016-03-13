# Translator
Translator App


This project has written and modified based on Derek Banas page, for more information please have a look at : 
https://www.youtube.com/watch?v=I58TkCi73ew

If some of you have any trouble with missing libraries (Cannot resolve token) on classes like DefaultHttpConnection, follow this simple steps:<br>
1. Go to File -> Project Structure.<br>
2. Under Modules click on 'app' and than change to the dependencies folder.<br>
3. Click on the green plus sign in the upper left area of the window.<br>
4. Select Library Dependency<br>
5. Write in the search box "org.apache.http" and hit Enter (or search).<br>
6. Select the one starting with org.jbundle.util.osgi.wrapped.<br>
7. Click Ok and Ok again to close the window. Your project should now refersh.<br>



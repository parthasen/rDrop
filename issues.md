#  Files that need  work
1. dropbox_save
2. dropbox_get
3. dropbox_move - working, but needs error atching!
4. dropbox_delete - working!
5. dropbox_copy - works but needs major error handling
6. dropbox_restore - haven't worked on it yet.
# Error handling
1. Check destinations for copy/move
2. Check file name formatting for copy/move for from and to.
3. Sort out issue with verifiying dropbox_cred
4. Big Bug: dropbox_auth() fails on R-GUI
4a. dropbox_auth() should not ask for a PIN.

# rdropbox issues
1. Authentication is successful from the R GUI but crashes the application while waiting for PIN input.
2. File upload also causes the same crashing behavior.
3.
<!-- Reference for the API
https://www2.dropbox.com/developers/reference/
 -->
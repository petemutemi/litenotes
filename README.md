# litenotes
Laravel Notes Management Project
	ü LiteNotes application - Understanding project requirements
		○ Features
			§ landing page
				□ tool links - login, register
					® new user to register with name, email, and password
						◊ creates a new account and logs the user in 
					® an existing user can login from the login page
					® will see all notes listed as soon as you login
					® notes ordered by showing the latest modified notes first
					® can see 5 notes per page and a pagination at the bottom
					® create new note at the top button
						◊ title
						◊ some text
							} both required, with an error flash prompt
					® click on any note title to view the full note
						◊ can see when it was created and last updated
						◊ options - edit or move to trash
							} on edit - see a flash message of note updated succesfully that disappears on page refresh
							} on move to trash - confirmation popup
								– deleted note can be found in trash
									w options - restore note, or delete forever
					® each note has a unique id
					® logout
		○ Quick summary
			§ 
![image](https://github.com/petemutemi/litenotes/assets/32926756/667f87c5-2ff6-41ed-8b4b-cdbd394f39d0)

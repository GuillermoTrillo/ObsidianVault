You can configure Git at:

- **System**: For every single user in the computer.
- **Global**: For all repositories of the current user.
- **Local:** The current repository.

When changing the configuration, you shall write "config" right after "git".

	 The first configurations you have to do are the User name and the User email, with these commands:  
 
#git #config #--global _user.name_ "Name Goes here"

#git #config #--global _user.email_ "Email goes here"

	Then, define the base code editor that Git is gonna use:

#git #config #--global _core.editor_ "code --wait"

	You can use -e to see the configurations in the base code editor.

#git #config #--global _-e_

	Because of how Windows sees what the End of the Line is differently than how Linux and MacOS does, this line is very much important so it doesn't do any type of problem.
	If it is Windows, use "true", if not, "input"

#git #config #--global _core.autocrlf_ true




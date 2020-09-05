# Server-Protection


# Table of contents

- Setting up the bot
- Auto modules
- Utility
- Resetting the bot



-------------------------------------

# Setting the member role

- !!setrole @role (must be a role mention)

- This sets the member role which will be useful for later purposes (will explain later on)

-------------------------------------

# Setting the admin role

- !!setadmin @role (must be a role mention)

- This sets the admin role so people with this role will have bypass features and won't be moderated.
- If you set this to a member role, then the bot will moderate you.

-------------------------------------

# Setting the muted role

- !!setmute @role (must be a role mention)

- This sets the muted role (will be useful for later)

-------------------------------------

# Setting Auto-Mod up

- !!setmod

- This enables the anti links features which will delete any links sent in the server.

- If you have the muted role setup (see !!setmute for more) then the anti spam filter will enable by itself.

-------------------------------------

# Setting up logger

- !!setlog #channel (must mention a channel)

- Any activity in the server will be logged to this channel

-------------------------------------

# Setting up welcome

- !!setwelcome #channel (must mention a channel)

- Will greet the user with a message in that channel when they join

- !!welcomemsg <message> (must be a message)
  
- This is optional but you can edit the welcome message if you wish

-------------------------------------

# Deleting/Resetting modules/Roles

- !!delmute (deletes muted role)
- !!delete (deletes member and admin roles)
- !!deletewelcome (deletes welcome channel)
- !!deletemod (deletes auto mod)
- !!deletelog (deletes logger)

-------------------------------------

# Verification System

- !!setverify #channel (sets the verification log channel)
- !!delverify (deletes the verification system)

game data is stored here.

we're gonna split the game into many files
welcome.py, tutorial.py, main.py, etc.

we're also gonna make battle.py, which will be a file that initiates a fight between you and whoever the parameters says (saves us from creating repeating fighting codes, just call a function from the file and put the parameters
as the opponent and you'd be able to create fights with a simple function call)

main.py is where the main game actually calls all these other py files
it'll go through welcome.py if there's no data in the db, then tutorial, etc.
then it'll save in the db that user has completed tutorial etc.


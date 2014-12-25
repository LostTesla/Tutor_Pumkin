Tutor_Pumkin
============

Hangman Code

private bool _keepPlaying = True;
private int _guessesLeft = 5;
private string _answer;
private int _lettersFound = 0; 

while(_keepPlaying != False)
{
	int _answerWordCount = length(_answer);
	
	if(guess == False)
	{	
		_guessesLeft = _guessesLeft - 1;
	}
	else
	{
		_lettersFound = _lettersFound + 1;
	}
	if(_lettersFound == _answerLetterCount)
	{
		Console.WriteLine("You Win!");
	}
	else
	{
		Console.WriteLine("You have " + _guessesLeft + " guesses left.");
	}

}

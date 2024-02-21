# INFO448-QuizDroid (Storage)
* An application that will allow users to take multiple-choice quizzes
* Now we will write the code to check the questions periodically, store the data, and allow for preferences

## Tasks
* Refactor the TopicRepository to read a local JSON file (data/questions.json) to use as the source of the Topics and Questions. Use a hard-coded file (available at http://tednewardsandbox.site44.com/questions.json) stored on the device for now
* The application should provide a "Preferences" action bar item that brings up a "Preferences" activity containing the application's configurable settings: URL to use for question data, and how often to check for new downloads measured in minutes. If a download is currently under way, these settings should not take effect until the next download starts.

## Implementation Notes
* Keep in mind in the next part, you're going to download that JSON file, so make sure that your code to open the file is flexible enough to read from a different location on the device
* Putting the file into the "assets" folder of the Android Studio project is easy, but can't be overwritten by what's downloaded

## Grading (5 pts)
* repo should be called 'quizdroid' on branch 'storage'
* 3 pts: TopicRepository pulls all data from a JSON file
* 2 pts: Preferences displays configuration

## Extra credit
* Use a custom JSON file of your own with your own questions; if you do this, submit screenshots using your questions. Include the URL at which your JSON file can be found (it must be Internet-accessible) so we can verify it. It must match the structure/format of the example. (2 pts)



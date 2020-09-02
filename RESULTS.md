## Material

### Instructions for Testing in Kotlin
1. Open the [Code](https://github.com/ianyehwork/CSC510_HW2/blob/master/kotlin/gameoflifebugged.kt) for GOL.
2. Copy the code and  paste it in the [online editor](https://play.kotlinlang.org/).
3. Click on Run button to check the output.

### Instructions for Testing in Processing
1. Open the [Code](https://github.com/ianyehwork/CSC510_HW2/blob/master/processing/game_of_life/game_of_life_bug.pde) for GOL.
2. Install the [processing editor](https://processing.org/download/).
3. Copy and paste the code in the editor.
4. Click on Run button to check the output.

### Instructions for Testing in Ruby
1. Navigate to the [online editor](https://repl.it/~) and create a Ruby workspace.
2. Copy and paste the [Code](https://github.com/ianyehwork/CSC510_HW2/blob/master/ruby/life_bug.rb) in the editor.
3. Click on Run button to check the output.

### Post Experiment Survey
All the participants are required to fill the [survey form](https://docs.google.com/forms/d/e/1FAIpQLSeAyvzNEJ6ozMKzJXRQOpA_AgN3aico8uZJ9fSEIe81Bukxow/viewform?usp=sf_link)

## Observations
Due to the fact that not all the participants have chance to finish debugging all the GOL version due to limited item or willingness, the following graph shows how many participants complete which GOL version. This can help us understand if there is bias towards the observation caused by insufficient data.

<img src="/image/Version_Participant_Count.png">

### How easy to debug certain language
1: Easy - 5: Hard

<img src="/image/Easy_Ruby.png">
<img src="/image/Easy_Kotlin.png">
<img src="/image/Easy_Proc.png">

### What is the hard part(s) about certain language

<img src="/image/Hard_Ruby.png">
<img src="/image/Hard_Kotlin.png">
<img src="/image/Hard_Proc.png">

### How likely will you learn certain language
1: Not Likely - 5: Most Likely

<img src="/image/Likely_Ruby.png">
<img src="/image/Likely_Kotlin.png">
<img src="/image/Likely_Proc.png">

## Conclusion
1. Clearly, participants found Ruby the easiest to debug while Processing to be the hardest one.  
2. Participants were unanimous that Ruby and Kotlin have different syntax types which confused them. Processing was difficult in syntax type as well as the flow and readability. 
3. Participants were more likely to learn Ruby after the experiment and least interested in Processing.  

## Threat to validity
There are a few things in our experiment that could pose a threat to validity and accuracy of the test. Following are some highlights -   
1. In order to debug different languages, different compilers were used at different websites. This interferes with standardization and the amount of time given to each debugger in a small but significant way. The ideal method should be to provide the same system to testers.  
2. The familiarity of each tester is with the language they debugged is not taken minutely into consideration. Due to different levels of comfort in different language, the results could show some difference than expected as this could provide ease to the one more comfortable in a particular language.  
3. Amount of data collected could have been more minute. The specific details in the analysis like the exact timings at which a bug was suspected and the amount of time fixed. Additionally calculating the number of attempts made and number of times compiled can also be useful measures.  
4. The constructs and the way codes were written varied with some amounts from language to language. The bugs are different from language to language. Though they were of similar level of difficulty, still do not pose an ideal environment to compare the results in an absolute way.  
5. Subjective analysis of the test is not described in detail. The data is usually collected in numbers which have fixed values. Due to this, some details from the tester’s as well as reviewer’s side could be incomplete. Thus a long subjective description can also be used to capture more details about the test.  

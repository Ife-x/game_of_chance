# game_of_chance

print('''
                                                                  .____   __ _
     __o__   _______ _ _  _                                     /     /
     \    ~\                                                  /      /
       \     '\                                         ..../      .'
        . ' ' . ~\                                      ' /       /
       .  _    .  ~ \  .+~\~ ~ ' ' " " ' ' ~ - - - - - -''_      /
      .  <#  .  - - -/' . ' \  __                          '~ - \
       .. -           ~-.._ / |__|  ( )  ( )  ( )  0  o    _ _    ~ .
     .-'                                               .- ~    '-.    -.
    <                      . ~ ' ' .             . - ~             ~ -.__~_. _ _
      ~- .       N121PP  .          . . . . ,- ~
            ' ~ - - - - =.   <#>    .         \.._
                        .     ~      ____ _ .. ..  .- .
                         .         '        ~ -.        ~ -.
                           ' . . '               ~ - .       ~-.
                                                       ~ - .      ~ .
                                                              ~ -...0..~. ____
   ''')
print("Welcome to the game of chance")
print("You get to win a trip to dubai")
first_choice = input('pick a card from the table, "Head" or "Tail"\n').lower()
#second_choice = input('Proceed to open the crest, "Golden balls" or  "silver ball"\n').lower()

if first_choice == "head":
  second_choice = input('Proceed to open the crest, "Golden balls" or  "silver balls"\n').lower()
  if second_choice == "golden balls":
     third_choice =input('Welcome to a whole new world, what do you want to do? turn "left" or "right"\n').lower()
     if third_choice == "left":
       print("Congratulations, you've won a trip to Dubai!.")
     else:
      print("Your game ends here, better luck next time.")
  else:
      print("Game over,try again next time")

else :
  print("Game over, you need to try again.")

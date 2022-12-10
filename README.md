# generate-a-random-story-
import random

when=['A few years ago', 'Yesterday', 'Last night', 'On 15th July']

who=['a rabbit', 'an elephant', 'a mouse', 'a tortoise', ' a lion', 'a dog', 'a crocodile', 'a tiger']

name=['Peter', 'Raghav', 'Ashish', 'Lavish', 'Pradeep', 'Sharad', 'Rishabh', 'Devang', 'Mukesh', 'Faraz']

residence=['India', 'America', 'Canada', 'Nepal', 'Korea', 'England', 'China', 'Germany', 'France', 'Belgium']

Went=['Cinema', 'University', 'School', 'Hotel', 'Water park', 'Zoo']

happend=['eats a pizza', 'wrote a book', 'eats an ice-cream', 'eats a burger', 'drinks a glass of juice']

went2=['a new city', 'an old village']

did_what=['made new friends,', 'interacted with new peoples,', 'met his old friends,']

after_that=['to visit their homes', 'to a cultural party']

then_he=['accepted their offer.', 'went along with them.']

there_he=['enjoyed a lot.', 'learned  alot about their culture and their traditions.', 'got some important lessons for his life.']

A=['enjoying a lot ', 'having a lot of fun']

decided=['return to his home.', 'say them good-bye.']

time=['5 pm', '6pm', '7pm', '8pm']

returned=['to his home']

in_home=['lays down on his bed', 'sits on his couch', 'sits on a chair']

writes=['writes in his diary', 'writes on a paper']

what=['he did today.', 'he learned today.', 'he need to do tommorow.']

End=['he wents to sleep.', 'he slept happily.']

S1=(random.choice(when) + ',' + random.choice(who) + ' named ' + random.choice(name) + ' who lived in '
      + random.choice(residence) + ',went to the ' + random.choice(Went) + ' and ' + random.choice(happend) +
      ' then he went to ' + random.choice(went2) + '\n' + ' where he ' + random.choice(did_what) +'\n'+
      ' who invited him ' + random.choice(after_that) + ' and he ' + random.choice(then_he)
      + ' There he ' + random.choice(there_he) +'\n' + 'After ' + random.choice(A) + ' he decided ' + random.choice(decided)
      + 'Around ' + random.choice(time) + ' he returned ' + random.choice(returned) + ' and ' + random.choice(in_home)
      + ' and ' + random.choice(writes) + '\n' + ' all the things ' + random.choice(what) + '\n' +
      ' Then with a smile on his face ' + random.choice(End))

books=['HARRY POTTER','THE CHAMBER OF SECRETS','DAVID-COPPERFIELD','THE MERCHANT OF VENICE','CINDERELLA,']

exposition=['Mr. and Mrs. Dursley of number four',' Not for the first time',
            'Whether I shall turned out to be the hero of my life',
            ' In a country named Venice Antonio worries','Once upon a time girl named,Harry']

characters=['This a fantastical story of a boy named Harry',
            'The hero and the protogonists,Harry',
            'David mother-Clara cooperfield, His old nurse-Pegotty',
            'Merchant named Antonio,his friend Bassanio and his enemy Shylock',
            'Cindrella ,her two step sisters and her fairy godmother']

time=['one day in a village','Second year of Hogwarts school of witchcraft and wizardy',
      'In the mid-age 1560s','In the mid 1596 and 1598','In the mid-to-late1800s']

story=['a boy who learned on his 18th bday that he was an orphanised son of two powerful wizards',
       'The second installment of the boy wizard Harry Potter','On his return David was given a good reason',
       'An antisemitic merchant who takes loan','Beautiful girl named cindrella who was women of good heart']

place=['Hogwarts school of witchcrafts and wizadry',
       'room built by salazar slytherin and hidden inside hogwarts',
       'Blunderstone ,Suffolk,England','In Italy','In France']

age=['Begins when Harry is 18th','A sixteen year teenager named Tom Riddle',
     'When David was in his mid-age','Antonio,merchant of fourteen years in age',
     'Cindrella, girl of good heart and 19 years old young girl']

work=['Ceramic and stoneware products using production machines',
      'Care-taker of Hogwarts-castle',' worked in family bottling factory',
      'Royal merchant in venice','worked as scullery maid']

S2=(random.choice(books)+'\n'+ random.choice(exposition)+'\n'+random.choice(characters)+
    random.choice(time)+"time"+'\n'+ random.choice(story)+"begins with"+random.choice(place)
    +" "+random.choice(age)+" "+random.choice(work))

who3=['A girl', 'A woman', 'A lady']

names3=['Celina', 'Mahima', 'Karishma']

Went3=['CLass', 'School']

happend=['eats a pizza', 'wrote a book', 'eats an ice-cream', 'eats a burger', 'drinks a glass of juice']

A=['enjoying a lot ', 'having a lot of fun']

decided=['return to his home.', 'say them good-bye.']

time=['5 pm', '6pm', '7pm', '8pm']

returned=['to his home']

in_home=['lays down on his bed', 'sits on his couch', 'sits on a chair']

writes=['writes in his diary', 'writes on a paper']

what=['he did today.', 'he learned today.', 'he need to do tommorow.']

End=['he wents to sleep.', 'he slept happily.']

S3= (random.choice(who3) + ' named ' +'\n'+ random.choice(names3) + ' Went to a ' + random.choice(Went3)+ ' and ' + random.choice(happend) +
      ' then he went to ' + random.choice(went2) + '\n' + ' where he ' + random.choice(did_what) +'\n'+
      ' who invited him ' + random.choice(after_that) + ' and he ' + random.choice(then_he)
      + ' There he ' + random.choice(there_he) +'\n' + 'After ' + random.choice(A) + ' he decided ' + random.choice(decided)
      + 'Around ' + random.choice(time) + ' he returned ' + random.choice(returned) + ' and ' + random.choice(in_home)
      + ' and ' + random.choice(writes) + '\n' + ' all the things ' + random.choice(what) + '\n' +
      ' Then with a smile on his face ' + random.choice(End))
AGE = int(input("Enter your age:"))
if 0 < AGE <= 10 and AGE>0:
    print(S1)
elif 10 < AGE <= 20 and AGE>0:
    print(S2)
elif AGE<=0:
    print("age cant be negative,check once again!")
else:
    print(S3)

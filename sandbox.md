# Open Template

## Follow the instructions of the teacher or make your own game with this tutorial
You will either be asked to code something from the teacher or make your own game.

```python
  #Code needed for Toolbox
  adventure.add_to_textlog("Hello!")
  adventure.add_image_to_text_log(img("""
    . . . . . . . . . . b b b . . .
    . . . . . . . . b e e 3 3 b . .
    . . . . . . b b e 3 2 e 3 a . .
    . . . . b b 3 3 e 2 2 e 3 3 a .
    . . b b 3 3 3 3 3 e e 3 3 3 a .
    b b 3 3 3 3 3 3 3 3 3 3 3 3 3 a
    b 3 3 3 d d d d 3 3 3 3 3 d d a
    b b b b b b b 3 d d d d d d 3 a
    b d 5 5 5 5 d b b b a a a a a a
    b 3 d d 5 5 5 5 5 5 5 d d d d a
    b 3 3 3 3 3 3 d 5 5 5 d d d d a
    b 3 d 5 5 5 3 3 3 3 3 3 b b b a
    b b b 3 d 5 5 5 5 5 5 5 d d b a
    . . . b b b 3 d 5 5 5 5 d d 3 a
    . . . . . . b b b b 3 d d d b a
    . . . . . . . . . . b b b a a .
"""))
  adventure.clear_text_log()
  adventure.change_log_colors(1, 9)
  x=1+1
  x=1-1
  x=1*1
  x=1/1
  x=randint(0, 10)
  item = 0
  x < 3 and x <4
  x< 3 or x == 1
  if True:
      pass
  if True:
      pass
  else:
      pass
  while True:
      pass
  for i in range(4):
      pass
  def do_something():
      pass
  scene.set_background_color(0)
  game.ask("Do you want to continue?")
  game.ask_for_number("How old are you?")
  game.ask_for_string("Enter your name: ")
  info.set_score(0)
  info.change_score_by(1)
```

```assetjson
{
  "README.md": " ",
  "assets.json": "",
  "images.g.jres": "{\n    \"image1\": {\n        \"data\": \"hwQfACAAAAD//////////7vbvbu7+///////////v7u7u727u7v/////////v727u7u9u7u7+///////vbu7u7u7vcy8u/v/////27u7u7u728vMzMy7///fu9u92927u9u7u7u7u/v/v7vbu9vdu7vbu7u7u7u7/7+7u7vd3bu727u7u7u7u/+/u927u7u7u9u7u7u7u9v/v7vbu7vbu7vbu7u7u8z8/7+7u7u7u7u73czLzMzM+/+/u7u7u7u7u83MzMzMzP//u7u7u7u7u9vLzMzMzLz//7u7u7u7u7u9zMzMzMz8/7+7u7u7u9vdy8zMzMzM/P+/u7u83d3dvczMzMzMzP//vbu7zNzd3czMzMzMzMz//7u7u8zMzMzMzMzMzMy8//+7u7vMzMzMzMzMzMzM/P//u7u7y8zMzMzMzMzMzPz//7u7u9u7u7u7u7vMzMz///+9u7vbu7u7u7u7y8zM////v7u727u7u7u7u8vMzP///7+7u9u7u8vMzMzMzLz/////u7vbzMzMzMzMzMz8/////7u7u8zMzMzMzMzM/f////+7u8vMzMzMzMzMzP//////v7vMzMzMzMzMzP3//////9/LzMzMzMzMzPz/////////z8zMzMzMzPv////////////fzMzM+///////////\",\n        \"mimeType\": \"image/x-mkcd-f4\",\n        \"displayName\": \"rock\"\n    },\n    \"image2\": {\n        \"data\": \"hwQfACAAAAD//+7+////////7u7u7v///727u////7+7u7u7u7u7///t3e3////v7u7d3d3d7v/v293dzu/u3t3d3evd3d3+79vd3e7e3d3t3d7L3d3d/u/b3d3u3t3d7d3ey93d3f7v293d7t3d3s3d3Mvd3d3+79vd3e7t29zN3dzL3d3d/u/b3d3u7dvczd3ey93d3f7v293d7s3b3M3d3cvd3d3+79vd3e7N29zN3d7d3d3d/u/b3d3uzdvdzd3c693d3f7v293d7s3b3c3d3Ovd3d3+79vd3e7N297N3dzL3d3d/u/b3d3uzdvczd3c3e3e3f7v293d7s3b3M3d3N3t3t3+79vd3e7N29zd3dzd7d/d/u/b3d3u3d3d7d3c3c3f3f7v293d7r3b283d3N29293+79vd3e7t297N3dzd3d3d/u/b7d7uzdvczd3d3e7u3f7v297t7s3b3d3dzOzd3e7+79ve7e7N293d3e7u3d3u/v/t3d3d3d3t7u7v293dvf7//97d3e3u3v//79vd3b3+//+7u7u7u9v//+/b3d29/v//7+7u/v/////v293dvf7/////////////79vd3e7//////////////9/r7u7/////////////////6+7u////////////////////////\",\n        \"mimeType\": \"image/x-mkcd-f4\",\n        \"displayName\": \"paper\"\n    },\n    \"image3\": {\n        \"data\": \"hwQfACAAAAD///////////////////////////////////////////////////////////////////8vIiL/////////////////LyIi/////////////////yLyL/L///////////////8i//8i////////////////L/L/L/L///////////////zi/Pzy////////////////Iv//8v///////////////y/yL/L/////////////////IiLy//////////////////8i3/z/////////////////It/8///////////////////dzczMzMzM////IiIiIiLy/d3d3d3d3cz//yLy/y8i8t3d3d3d3d3d/P8iz8z8Is+7u7u7u7u7u/z/Iv///yLPzMzMzMzMzMz8/yL//y/y///Pu8v///////8v8v8i/////7y7/P///////yIi8v/////Pu8v///////8iIvL/////z7vL//////////////////+8u/z/////////////////z7vL//////////////////+8u8z/////////////////y7zL/////////////////8+8y///////////////////z8z/////////////////////////////////////////////\",\n        \"mimeType\": \"image/x-mkcd-f4\",\n        \"displayName\": \"scissors\"\n    },\n    \"*\": {\n        \"mimeType\": \"image/x-mkcd-f4\",\n        \"dataEncoding\": \"base64\",\n        \"namespace\": \"myImages\"\n    }\n}",
  "images.g.ts": "// Auto-generated code. Do not edit.\nnamespace myImages {\n\n    helpers._registerFactory(\"image\", function(name: string) {\n        switch(helpers.stringTrim(name)) {\n            case \"image1\":\n            case \"rock\":return img`\nffffffffffffffffdbbbbdfffffffff\nffffffffffffffbbbbbbbbbbfffffff\nffffffffffffbbbbbbbbbbbbbbbffff\nfffffdbbbbbbbbbbbbbbbbbbbbbbdff\nfffffbbbbbbbbbbbbbbbbbbbbbbbbff\nfffffbbbbbbbbbbbbbbbbbbbbbbbccf\nffffbbbbdbbbbbbccccbbbbbbbbcccf\nffffdddbddbbbbbbccccdddddbccccd\nfffdbdbbbbbbbbbdccccbbbbccccccc\nfffbbbbbbbbbbbbddcccbbbbccccccc\nfffbbbbdbbbbbbbddcccbbbbccccccc\nffbbbdddbbbbbbbddcccbbbbccccccc\nffdbbdddbbbbbbbddcccbbbbccccccc\nfbbbbdddbdbbbbdddcccbbbcccccccc\nfbbbbbbbbbbbbbddccccbbbcccccccb\nfbbbbbbbbbbbbbdbccccbbbcccccccf\nbbbbbbbbbbbbbdbcccccbbbcccccccf\nbbbbbbbbbbbbdbccccccbbbcccccccf\nbbbbbbbbbbddbcccccccbbbccccccbf\ndbbbdddddddcccccccccbbbccccccff\nddddbbbbbbcccccccccccbbccccccff\nbbbbcbbbbbccccccccccccccccccfff\nbbbccbbbbbbccccccccccccccccdfff\nbbbccbbbbbcccccccccccccccccffff\nbbbccbbbbbcccccccccccccccdfffff\nbbbbcbbbbbcccccccccccccbfffffff\nbbbbcbbbbbccccccccccfffffffffff\nfbbbcbbbbbcccccccbfffffffffffff\nffbbbbbbbccccccffffffffffffffff\nffffbbbbbcccbffffffffffffffffff\nfffffbbbbcbffffffffffffffffffff\nffffffbbdffffffffffffffffffffff\n`;\n            case \"image2\":\n            case \"paper\":return img`\nfffffffffffffffffffffffffffffff\nfffeeeeeeeeeeeeeeeeeeeeffffffff\nfddbbbbbbbbbbbbbbbbbbbbdfffffff\nfbeddddddddddddddddddddefffffff\nebdddddddddddddddddddeedebfffff\nebddddddddddddddddddeddddbeffff\nebddddddddddddddddddeddddbeffff\nfbeddddddddddddddddddeeddbeffff\nfffeeeeeeeeeeeeeeeeeeeeddbeffff\nfffceeeeeeeeeeeeeeeeeeeddbeffff\nffffeedddddddddddddddddddbeffff\nfffedddeeccccccccdbecccdebfffff\nfffedddbbbbbbbbbbdbbbbbdebfffff\nfffeddddddddddddddddddddebfffff\nfffeddeccccddecccdbecdddebfffff\nfbeddddddddddddddddddddeddfffff\nfbeddddddddddddddddddddefffffff\nfbedeeccccccccccdecccddefffffff\nfbeddddddddddddddddddddefffffff\nfbeddddddddddddddddddddefffffff\nebddeeccedecccccccccdceffffffff\nebdddddddddddddddddddceeeeeedff\nebdbbbbbbbdbbbdddddddcebbbbbbbf\nebdeccccccdeecdddddddeedddddeef\nebddddddddddddddddddedddddddeef\nebddddddddddddeeecbdedddddddeef\nebddddddddddddeeffbdedddddddeef\nebddddddddddddddddddedddddddeef\nfbeddddddddddddddddddeeddddefff\nfbeddddddddddddddddddeebbbbefff\nfffeeeeeeeeeeeeeeeeeeeeeeeeffff\nfffffffffffffffffffffffffffffff\n`;\n            case \"image3\":\n            case \"scissors\":return img`\nfffffffffffffffffffffffffffffff\nfffffffffffffffffffffffffffffff\nfffffffffffffff22222fffffffffff\nfffffffffffffff222222ffffffffff\nfffffffffffffff22fff222ffffffff\nfffffffffffffff2fcfff22ffffffff\nfffff22fcffffff2fcfff22ffffffff\nfff22222fffffff2fcfff22ffffffff\nfff222f222fffff2fcff222ffffffff\nfff22fffe22ffff22ff22ffffffffff\nfff22fffcf22fff22222fffffffffff\nfff222fffff2fff2222ffffffffffff\nfffff22fcff222f22ffffffffffffff\nffffff22ff2222fffccffffffffffff\nfffffff22222ffdddbcffffffffffff\nffffffffffffdddfdbcffffffffffff\nffffffffffffccdddbcffffffffffff\nffffffffffffffcddbccfffffffffff\nffffffffffffffcddbcbcffffffffff\nffffffffffffffcddbcbbccffffffff\nffffffffffffffcddbcbbbbcfffffff\nffffffffffffffcddbccbbbbcffffff\nffffffffffffffcddbcfcbbbbcbffff\nffffffffffffffcddbcffccbbbccfff\nffffffffffffffcddbcffffcbbccfff\nffffffffffffffcddbcfffffcbbbcff\nffffffffffffffcddbcffffffcbbcff\nffffffffffffffcddbcffffffccccff\nfffffffffffffffcdbcffffffffffff\nfffffffffffffffcdbcffffffffffff\nffffffffffffffffcccffffffffffff\nfffffffffffffffffffffffffffffff\n`;\n        }\n        return null;\n    })\n\n    helpers._registerFactory(\"animation\", function(name: string) {\n        switch(helpers.stringTrim(name)) {\n\n        }\n        return null;\n    })\n\n    helpers._registerFactory(\"song\", function(name: string) {\n        switch(helpers.stringTrim(name)) {\n\n        }\n        return null;\n    })\n\n}\n// Auto-generated code. Do not edit.\n",
  "main.blocks": "<xml xmlns=\"https://developers.google.com/blockly/xml\"><variables><variable id=\"I:Z8+|t/xBKctMz|C61d\">item</variable><variable id=\"*Eks#,q]+wrPQIJhTttG\">mySprite</variable><variable type=\"KIND_SpriteKind\" id=\"oh:mMF}+s/1fq!FNh`g?\">Player</variable><variable type=\"KIND_SpriteKind\" id=\"H}{3TM-5sH*S4/cN.Vi[\">Projectile</variable><variable type=\"KIND_SpriteKind\" id=\"nj4i-lrQx^`Ze|SUO;|L\">Food</variable><variable type=\"KIND_SpriteKind\" id=\";eSIMfX/fs_nKZY-WH0Y\">Enemy</variable></variables><block type=\"pxt-on-start\" x=\"0\" y=\"0\"></block></xml>",
  "main.py": "display_rock()\ndisplay_paper()\ndisplay_scissors()\nadventure.add_to_textlog(\"Time to play Rock, Paper, or Scissors!\")\nadventure.add_to_textlog(\"Best of Three\")\nplayer_score = 0\ncomputer_score = 0\nwhile player_score < 2 and computer_score < 2:\n    player_num = game.ask_for_number(\"What will you play? 1=Rock, 2=Paper, and 3=Scissors\")\n    if player_num == 1:\n        adventure.add_to_textlog(\"You Play Rock!\")\n        display_rock()\n    elif player_num == 2:\n        adventure.add_to_textlog(\"You Play Paper!\")\n        display_paper()\n    else:\n        adventure.add_to_textlog(\"You Play Scissors!\")\n        display_scissors()\n    computer_num = randint(1,3)\n    if computer_num == 1:\n        adventure.add_to_textlog(\"Computer Plays Rock!\")\n        display_rock()\n    elif computer_num == 2:\n        adventure.add_to_textlog(\"Computer Plays Paper!\")\n        display_paper()\n    else:\n        adventure.add_to_textlog(\"Computer Plays Scissors!\")\n        display_scissors()\n    if computer_num == 1 and player_num == 2 or computer_num == 2 and player_num == 3 or computer_num == 3 and player_num == 1:\n        computer_score +=1\n        adventure.add_to_textlog(\"Player Wins!\")\n    elif player_num == 1 and computer_num == 2 or player_num == 2 and computer_num == 3 or player_num == 3 and computer_num == 1:\n        player_score +=1\n        adventure.add_to_textlog(\"Computer Wins!\")\n    else:\n        adventure.add_to_textlog(\"Tie!\")\n    \n\ndef display_rock():\n    adventure.add_image_to_text_log(assets.image(\"\"\"rock\"\"\"))\n\ndef display_paper():\n    adventure.add_image_to_text_log(assets.image(\"\"\"paper\"\"\"))\n\ndef display_scissors():\n    adventure.add_image_to_text_log(assets.image(\"\"\"scissors\"\"\"))\n    \n",
  "main.ts": "let player_num: number;\nlet computer_num: number;\ndisplay_rock()\ndisplay_paper()\ndisplay_scissors()\nadventure.addToTextlog(\"Time to play Rock, Paper, or Scissors!\")\nadventure.addToTextlog(\"Best of Three\")\nlet player_score = 0\nlet computer_score = 0\nwhile (player_score < 2 && computer_score < 2) {\n    player_num = game.askForNumber(\"What will you play? 1=Rock, 2=Paper, and 3=Scissors\")\n    if (player_num == 1) {\n        adventure.addToTextlog(\"You Play Rock!\")\n        display_rock()\n    } else if (player_num == 2) {\n        adventure.addToTextlog(\"You Play Paper!\")\n        display_paper()\n    } else {\n        adventure.addToTextlog(\"You Play Scissors!\")\n        display_scissors()\n    }\n    \n    computer_num = randint(1, 3)\n    if (computer_num == 1) {\n        adventure.addToTextlog(\"Computer Plays Rock!\")\n        display_rock()\n    } else if (computer_num == 2) {\n        adventure.addToTextlog(\"Computer Plays Paper!\")\n        display_paper()\n    } else {\n        adventure.addToTextlog(\"Computer Plays Scissors!\")\n        display_scissors()\n    }\n    \n    if (computer_num == 1 && player_num == 2 || computer_num == 2 && player_num == 3 || computer_num == 3 && player_num == 1) {\n        computer_score += 1\n        adventure.addToTextlog(\"Player Wins!\")\n    } else if (player_num == 1 && computer_num == 2 || player_num == 2 && computer_num == 3 || player_num == 3 && computer_num == 1) {\n        player_score += 1\n        adventure.addToTextlog(\"Computer Wins!\")\n    } else {\n        adventure.addToTextlog(\"Tie!\")\n    }\n    \n}\nfunction display_rock() {\n    adventure.addImageToTextLog(assets.image`rock`)\n}\n\nfunction display_paper() {\n    adventure.addImageToTextLog(assets.image`paper`)\n}\n\nfunction display_scissors() {\n    adventure.addImageToTextLog(assets.image`scissors`)\n}\n\n",
  "pxt.json": "{\n    \"name\": \"Rock Paper Scissors\",\n    \"description\": \"\",\n    \"dependencies\": {\n        \"device\": \"*\",\n        \"story\": \"github:riknoll/arcade-story#v1.3.1\",\n        \"adventure\": \"github:microsoft/arcade-tutorial-extensions/adventure#v0.0.16\"\n    },\n    \"files\": [\n        \"main.blocks\",\n        \"main.ts\",\n        \"README.md\",\n        \"assets.json\",\n        \"main.py\",\n        \"images.g.jres\",\n        \"images.g.ts\"\n    ],\n    \"targetVersions\": {\n        \"branch\": \"v1.13.37\",\n        \"tag\": \"v1.13.37\",\n        \"commits\": \"https://github.com/microsoft/pxt-arcade/commits/f538f544699a0cf30bc4178a7a7b10440cd7dff3\",\n        \"target\": \"1.13.37\",\n        \"pxt\": \"9.1.13\"\n    },\n    \"preferredEditor\": \"pyprj\"\n}\n"
}
```

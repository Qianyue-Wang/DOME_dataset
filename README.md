# DOME_dataset
This is the repository for stories generated by DOME and stories used during the experiment section.

## Sturcture of story
We  name every story in number. 
Stories for method comparison are stored in /stories and was organized as follow:
```
stories
    ├─19
        │      doc_outline.txt   #the outline used in DOC
        │      re3_story.txt   #the story generated by RE3
        │      re3_outline.txt   #the outline used in RE3
        │      ours_outline.txt  #the outline used in DOME(our method)
        │      outline.txt  #the outline requirements of story
        │      doc_story.txt  #the story generated by DOC
        │      character.txt  #the character introduction of story
        │      llama_story.txt  #the story generated by directly intructing Llama3-70B-instruct
        │      setting.txt  #the setting of story
        │      qwen_story.txt  #the story generated by directly intructing Qwen1.5-72B-chat
        │      ours_story.txt  #the story generated by DOME(our method)
        │      llama_outline.txt  #the outline used by directly intructing Llama3-70B-instruct
        │      qwen_outline.txt  #the outline used by directly intructing Qwen1.5-72B-chat
    ├─8
    ├─3
    ├─15
    ├─9
    ├─20
    ├─12
    ├─10
    ├─2
    ├─4
    ├─11
    ├─1
    ├─16
    ├─5
    ├─14
    ├─18
    ├─13
    ├─7
    ├─17
    └─6
```
Since the files in every sub directory are organized in the same way, we only annotated the contents of one sub folders.


Stories for absolution comparison are stored in /absolution_stories and was organized as follow:
```
stories
    ├─19
        │      ours_outline.txt  ##the outline used in DOME(our method)
        │      outline.txt ##the outline requirements of story
        │      character.txt  ##the character introduction of story
        │      ab_KGself_story.txt  ##the story generated by ablating the MEM module using DOME.
        │      setting.txt  ##the setting of story
        │      ab_KGself_outline.txt  ##the outline used by ablating the MEM module using DOME.
        │      our_story.txt  ##the story generated by DOME.
        │      ab_dynamic_outline.txt ##the outline used by ablating the DHO module using DOME.
        │      ab_dynamic_story.txt  ##the story generated by ablating the DHO module using DOME.
    ├─8
    ├─3
    ├─15
    ├─9
    ├─20
    ├─12
    ├─10
    ├─2
    ├─4
    ├─11
    ├─1
    ├─16
    ├─5
    ├─14
    ├─18
    ├─13
    ├─7
    ├─17
    └─6
```

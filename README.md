# ButtonsGridExample
An example to learn how to dynamically add some button images into a grid

Here I'm creating some random button images and by pressing them showing some internal information about them. 

Ue4 elements created: 
- HUD
- PAWN
- GameMode 
- Some Widget BP classes: 
  - HUD_Start ( a widget BP class created from myHUD containing --> UI_ButtonsGridPanel )
  - UI_Button ( a canvas with a button with image inherited )
  - UI_ButtonsGridPanel ( a canvas with a grid panel to insert our dynamic items (UI_Button elements into UniformGridPanel)
  
-------------------
WIP
- I'm having issues to see that dyanmic elements. Open question at Ue4 Bp forum [https://forums.unrealengine.com/development-discussion/blueprint-visual-scripting/1462689-issues-adding-dynamically-some-button-images-into-my-ui]

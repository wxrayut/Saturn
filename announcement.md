
# Announcement

Just wanted to drop a quick note to all who is starting using this tool for creating mods/skins. I'm very happy that people are using the tools I created. Lately, though, I've noticed a few individuals trying to make a money by selling my tool without permission from me. It's disheartening to witness the commercial exploitation of something that was intended to be freely accessible. 

Regrettably, I feel compelled to announce that there will be no further updates or enhancements provided for this script in the future.

### Can the tool still be used?

Of course! you can still use it. But the only thing that will definitely have problems is the `CommonAction.pkg.bytes` file. Because this is a file for modify to creating `Recall effect` and `Sprint effect` for special skins.

When the game receives updates from the official developers, there is a risk that certain files may undergo changes. These alterations, particularly those affecting `CONDITION_ID` used to define various of effect elements, can introduce defects. 

#### In the case of making multiple skins.
- Your character may have multiple `Recall effect` on one character.

#### In the case of making a single skins.
- The `Recall effect` might not be displayed correctly.

#### You can check modified data with this path.

| File Path                                                 | Type            |
| --------------------------------------------------------- | --------------- |
| `CommonAction.pkg.bytes/commonresource/Back.xml`          | Recall effect   |
| `CommonAction.pkg.bytes/commonresource/HasteE1.xml`       | Sprint effect   |
| `CommonAction.pkg.bytes/commonresource/HasteE1_leave.xml` | Sprint effect   |

And if there is a new skin The `Recall effect` or `Sprint effect` cannot be performed because `SKIN_ID` is not added to lists.

#### Note: May include the `Sprint effect` as well.

### About Character Model and Skill files.

| File                          | Type            |
| ----------------------------- | --------------- |
| `Actor_105_Infos.pkg.bytes`   | Character Model |
| `Actor_105_Actions.pkg.bytes` | Skills          |  

#### Character Model
- The tool can find position of skin elements and create it.

#### Skills
- The tool can find the desired location and edit it.

These file have pattern to modify as the same, therefore code for modify these file is quite good, Very few cases will cause problems.

### Example problems

#### Character Model
- **Nakroth : Killua :** Needs to change the tag names of some elements.
- **Tachi : Garden of Awe :** Needs to create additional elements. If not, the model won't move.

#### Skills
- **Hayate : Shangrila Origin :** Needs to create additional elements to xml files, for complete skill effects.

If the game has updated with new skins beyond the mentioned examples, the tool should still function normally.
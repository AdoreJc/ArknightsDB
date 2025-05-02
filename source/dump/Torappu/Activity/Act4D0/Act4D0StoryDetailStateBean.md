# Act4D0StoryDetailStateBean

**Namespace:** `Torappu.Activity.Act4D0`


## Fields

- `String stageTitle`

- `String stageDesc`

- `String storyKey`

- `String storyId`

- `String storySort`

- `Boolean isNewStory`


## Methods

- `Void SetData(Act4D0StoryItemViewModel)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act4D0
public class Act4D0StoryDetailStateBean : MonoBehaviour, IStateBean, IHotfixable
{
	public String stageTitle; // 0x18
	public String stageDesc; // 0x20
	public String storyKey; // 0x28
	public String storyId; // 0x30
	public String storySort; // 0x38
	public Boolean isNewStory; // 0x40
	private static DelegateBridge __Hotfix0_SetData; // 0x0
	private static DelegateBridge _c__Hotfix0_ctor; // 0x8


	// RVA: 0x31dfbfc VA: 0x75957f7bfc
	public Void SetData(Act4D0StoryItemViewModel model) { }
	// RVA: 0x31e2754 VA: 0x75957fa754
	public Void .ctor() { }
}
```
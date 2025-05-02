# Act10D5StoryBinder

**Namespace:** `Torappu.Activity.Act10D5`


## Fields

- `SimpleLayoutContent _viewContainer`

- `Act10D5StoryAdapter m_storyAdapter`

- `Boolean m_isInited`


## Methods

- `Void _InitIfNot()`

- `Void SetCallbacks(Action`1, Action`1, Action`1)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act10D5
public class Act10D5StoryBinder : DataBinder`1, IHotfixable
{
	private SimpleLayoutContent _viewContainer; // 0x20
	private Act10D5StoryAdapter m_storyAdapter; // 0x28
	private Boolean m_isInited; // 0x30
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x0
	private static DelegateBridge __Hotfix0_OnValueChanged; // 0x8
	private static DelegateBridge __Hotfix0_SetCallbacks; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18


	// RVA: 0x3482fc0 VA: 0x7595a9afc0
	private Void _InitIfNot() { }
	// RVA: 0x348308c VA: 0x7595a9b08c
	public override Void OnValueChanged(Act10D5StoryProperty property) { }
	// RVA: 0x3483258 VA: 0x7595a9b258
	public Void SetCallbacks(Action`1 onReviewStoryClicked, Action`1 onUnlockStoryClicked, Action`1 onStoryRead) { }
	// RVA: 0x3483330 VA: 0x7595a9b330
	public Void .ctor() { }
}
```
# Act10D5StoryAdapter

**Namespace:** `Torappu.Activity.Act10D5`


## Fields

- `Color m_storyColor`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act10D5
public class Act10D5StoryAdapter : SimpleLayoutAdapter, IHotfixable
{
	public List`1 m_storyModels; // 0x20
	public Color m_storyColor; // 0x28
	public Action`1 onReviewStoryClicked; // 0x38
	public Action`1 onUnlockStoryClicked; // 0x40
	public Action`1 onStoryRead; // 0x48
	private static DelegateBridge __Hotfix0_get_count; // 0x0
	private static DelegateBridge __Hotfix0_RenderView; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public override Int32 count { get; }

	// RVA: 0x3481cd8 VA: 0x7595a99cd8
	public override Int32 get_count() { }
	// RVA: 0x3481d58 VA: 0x7595a99d58
	public override GameObject RenderView(Int32 position, GameObject prefab, Transform parent) { }
	// RVA: 0x3481f40 VA: 0x7595a99f40
	public Void .ctor() { }
}
```
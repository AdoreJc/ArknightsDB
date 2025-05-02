# MiniReviewDetailAdapter

**Namespace:** `Torappu.UI.StoryReview`


## Fields

- `Color m_storyColor`

- `Boolean m_ActivityOutOfTime`

- `GameObject m_customInfoPrefab`

- `GameObject m_customLockPrefab`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.StoryReview
public class MiniReviewDetailAdapter : SimpleLayoutAdapter, IHotfixable
{
	public List`1 m_storyModels; // 0x20
	public Color m_storyColor; // 0x28
	public Boolean m_ActivityOutOfTime; // 0x38
	public Action`1 onReviewStoryClicked; // 0x40
	public Action`1 onUnlockStoryClicked; // 0x48
	public Action`1 onStoryRead; // 0x50
	private GameObject m_customInfoPrefab; // 0x58
	private GameObject m_customLockPrefab; // 0x60
	private static DelegateBridge _c__Hotfix0_ctor; // 0x0
	private static DelegateBridge __Hotfix0_get_count; // 0x8
	private static DelegateBridge __Hotfix0_RenderView; // 0x10

	public override Int32 count { get; }

	// RVA: 0x275d35c VA: 0x7594d7535c
	public Void .ctor(GameObject customInfo, GameObject customLock) { }
	// RVA: 0x275d46c VA: 0x7594d7546c
	public override Int32 get_count() { }
	// RVA: 0x275d4ec VA: 0x7594d754ec
	public override GameObject RenderView(Int32 position, GameObject prefab, Transform parent) { }
}
```
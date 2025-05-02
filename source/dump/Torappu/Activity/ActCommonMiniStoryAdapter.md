# ActCommonMiniStoryAdapter

**Namespace:** `Torappu.Activity`


## Fields

- `Color m_storyColor`

- `GameObject m_customPrefab`

- `GameObject m_customLockPrefab`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity
public class ActCommonMiniStoryAdapter : SimpleLayoutAdapter, IHotfixable
{
	public List`1 m_storyModels; // 0x20
	public Color m_storyColor; // 0x28
	public Action`1 onReviewStoryClicked; // 0x38
	public Action`1 onUnlockStoryClicked; // 0x40
	public Action`1 onStoryRead; // 0x48
	private GameObject m_customPrefab; // 0x50
	private GameObject m_customLockPrefab; // 0x58
	private static DelegateBridge __Hotfix0_get_count; // 0x0
	private static DelegateBridge _c__Hotfix0_ctor; // 0x8
	private static DelegateBridge __Hotfix0_RenderView; // 0x10

	public override Int32 count { get; }

	// RVA: 0x30c8b5c VA: 0x75956e0b5c
	public override Int32 get_count() { }
	// RVA: 0x30c8bdc VA: 0x75956e0bdc
	public Void .ctor(GameObject customInfoPrefab, GameObject customLockPrefab) { }
	// RVA: 0x30c8ce4 VA: 0x75956e0ce4
	public override GameObject RenderView(Int32 position, GameObject prefab, Transform parent) { }
}
```
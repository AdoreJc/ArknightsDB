# Act42D0RewardTitleView

**Namespace:** `Torappu.Activity.Act42D0`


## Fields

- `SimpleLayoutContent _content`

- `Boolean m_isInited`

- `String m_cachedActId`

- `Int32 m_maxCount`

- `Adapter m_adapter`


## Methods

- `Void Render(ListDict`2, Int32, String)`

- `Void _InitIfNot()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act42D0
public class Act42D0RewardTitleView : MonoBehaviour, IHotfixable
{
	private SimpleLayoutContent _content; // 0x18
	private Boolean m_isInited; // 0x20
	private ListDict`2 m_cachedViewModels; // 0x28
	private String m_cachedActId; // 0x30
	private Int32 m_maxCount; // 0x38
	private Adapter m_adapter; // 0x40
	private static DelegateBridge __Hotfix0_Render; // 0x0
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10


	// RVA: 0x3221458 VA: 0x7595839458
	public Void Render(ListDict`2 titles, Int32 ratingMaxCount, String actId) { }
	// RVA: 0x322152c VA: 0x759583952c
	private Void _InitIfNot() { }
	// RVA: 0x32216e0 VA: 0x75958396e0
	public Void .ctor() { }
}
```
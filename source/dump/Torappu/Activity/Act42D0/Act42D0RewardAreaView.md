# Act42D0RewardAreaView

**Namespace:** `Torappu.Activity.Act42D0`


## Fields

- `SimpleLayoutContent _content`

- `Boolean m_isInited`

- `String m_cachedAreaId`

- `Adapter m_adapter`


## Methods

- `Void Render(String, ListDict`2)`

- `Void _InitIfNot()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act42D0
public class Act42D0RewardAreaView : MonoBehaviour, IHotfixable
{
	private SimpleLayoutContent _content; // 0x18
	private Boolean m_isInited; // 0x20
	private ListDict`2 m_cachedViewModels; // 0x28
	private String m_cachedAreaId; // 0x30
	private Adapter m_adapter; // 0x38
	private static DelegateBridge __Hotfix0_Render; // 0x0
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10


	// RVA: 0x321e884 VA: 0x7595836884
	public Void Render(String selectedAreaId, ListDict`2 areas) { }
	// RVA: 0x321e940 VA: 0x7595836940
	private Void _InitIfNot() { }
	// RVA: 0x321eaf4 VA: 0x7595836af4
	public Void .ctor() { }
}
```
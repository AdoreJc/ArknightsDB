# ActCommonFavorUpView

**Namespace:** `Torappu.Activity`


## Fields

- `SimpleLayoutContent _newUpGroup`

- `SimpleLayoutContent _upGroup`

- `GameObject _imageNew`

- `GameObject _panelSplit`

- `ActFavorUpGroupViewAdapter m_newUpGroupAdapter`

- `ActFavorUpGroupViewAdapter m_upGroupAdapter`

- `Boolean m_inited`


## Methods

- `Void Render(List`1, String)`

- `Void _InitIfNot()`

- `Int32 _CompareFavorUpChar(ActFavorUpCharData, ActFavorUpCharData)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity
public class ActCommonFavorUpView : MonoBehaviour, IHotfixable
{
	private SimpleLayoutContent _newUpGroup; // 0x18
	private SimpleLayoutContent _upGroup; // 0x20
	private GameObject _imageNew; // 0x28
	private GameObject _panelSplit; // 0x30
	private List`1 m_newUpCharList; // 0x38
	private List`1 m_upCharList; // 0x40
	private ActFavorUpGroupViewAdapter m_newUpGroupAdapter; // 0x48
	private ActFavorUpGroupViewAdapter m_upGroupAdapter; // 0x50
	private Boolean m_inited; // 0x58
	private static DelegateBridge __Hotfix0_Render; // 0x0
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x8
	private static DelegateBridge __Hotfix0__CompareFavorUpChar; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18


	// RVA: 0x30c4920 VA: 0x75956dc920
	public Void Render(List`1 favorList, String actId) { }
	// RVA: 0x30c4f94 VA: 0x75956dcf94
	private Void _InitIfNot() { }
	// RVA: 0x30c50b8 VA: 0x75956dd0b8
	private Int32 _CompareFavorUpChar(ActFavorUpCharData lhs, ActFavorUpCharData rhs) { }
	// RVA: 0x30c5160 VA: 0x75956dd160
	public Void .ctor() { }
}
```
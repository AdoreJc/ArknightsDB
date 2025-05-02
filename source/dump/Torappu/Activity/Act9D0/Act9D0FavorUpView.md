# Act9D0FavorUpView

**Namespace:** `Torappu.Activity.Act9D0`


## Fields

- `SimpleLayoutContent _newUpGroup`

- `SimpleLayoutContent _upGroup`

- `GameObject _imageNew`

- `GameObject _panelSplit`

- `Act9D0FavorUpGroupViewAdapter m_newUpGroupAdapter`

- `Act9D0FavorUpGroupViewAdapter m_upGroupAdapter`

- `Boolean m_inited`


## Methods

- `Void Render()`

- `Void _InitIfNot()`

- `Int32 _CompareFavorUpChar(Act9D0FavorUpCharData, Act9D0FavorUpCharData)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act9D0
public class Act9D0FavorUpView : MonoBehaviour, IHotfixable
{
	private SimpleLayoutContent _newUpGroup; // 0x18
	private SimpleLayoutContent _upGroup; // 0x20
	private GameObject _imageNew; // 0x28
	private GameObject _panelSplit; // 0x30
	private List`1 m_newUpCharList; // 0x38
	private List`1 m_upCharList; // 0x40
	private Act9D0FavorUpGroupViewAdapter m_newUpGroupAdapter; // 0x48
	private Act9D0FavorUpGroupViewAdapter m_upGroupAdapter; // 0x50
	private Boolean m_inited; // 0x58
	private static DelegateBridge __Hotfix0_Render; // 0x0
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x8
	private static DelegateBridge __Hotfix0__CompareFavorUpChar; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18


	// RVA: 0x31a4d70 VA: 0x75957bcd70
	public Void Render() { }
	// RVA: 0x31a5278 VA: 0x75957bd278
	private Void _InitIfNot() { }
	// RVA: 0x31a539c VA: 0x75957bd39c
	private Int32 _CompareFavorUpChar(Act9D0FavorUpCharData lhs, Act9D0FavorUpCharData rhs) { }
	// RVA: 0x31a5444 VA: 0x75957bd444
	public Void .ctor() { }
}
```
# Act10D5FavorUpView

**Namespace:** `Torappu.Activity.Act10D5`


## Fields

- `SimpleLayoutContent _newUpGroup`

- `SimpleLayoutContent _upGroup`

- `GameObject _imageNew`

- `GameObject _panelSplit`

- `Act10D5FavorUpGroupViewAdapter m_newUpGroupAdapter`

- `Act10D5FavorUpGroupViewAdapter m_upGroupAdapter`

- `Boolean m_inited`


## Methods

- `Void Render()`

- `Void _InitIfNot()`

- `Int32 _CompareFavorUpChar(Act10D5FavorUpCharData, Act10D5FavorUpCharData)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act10D5
public class Act10D5FavorUpView : MonoBehaviour, IHotfixable
{
	private SimpleLayoutContent _newUpGroup; // 0x18
	private SimpleLayoutContent _upGroup; // 0x20
	private GameObject _imageNew; // 0x28
	private GameObject _panelSplit; // 0x30
	private List`1 m_newUpCharList; // 0x38
	private List`1 m_upCharList; // 0x40
	private Act10D5FavorUpGroupViewAdapter m_newUpGroupAdapter; // 0x48
	private Act10D5FavorUpGroupViewAdapter m_upGroupAdapter; // 0x50
	private Boolean m_inited; // 0x58
	private static DelegateBridge __Hotfix0_Render; // 0x0
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x8
	private static DelegateBridge __Hotfix0__CompareFavorUpChar; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18


	// RVA: 0x3486e48 VA: 0x7595a9ee48
	public Void Render() { }
	// RVA: 0x34872f4 VA: 0x7595a9f2f4
	private Void _InitIfNot() { }
	// RVA: 0x3487418 VA: 0x7595a9f418
	private Int32 _CompareFavorUpChar(Act10D5FavorUpCharData lhs, Act10D5FavorUpCharData rhs) { }
	// RVA: 0x34874c0 VA: 0x7595a9f4c0
	public Void .ctor() { }
}
```
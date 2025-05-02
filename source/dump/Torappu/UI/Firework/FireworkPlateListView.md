# FireworkPlateListView

**Namespace:** `Torappu.UI.Firework`


## Fields

- `SimpleLayoutContent _plateListLeft`

- `SimpleLayoutContent _plateListRight`

- `GameObject _pnlPlateLocked`

- `FireworkPlateSubListView _subListView`

- `Image _scrollHandler`

- `FireworkPlateGroupModel m_cachedGroupModel`

- `FireworkPlateGroupViewStyle m_cachedStyle`

- `Adapter m_leftAdapter`

- `Adapter m_rightAdapter`

- `Boolean m_inited`


## Methods

- `Void _InitIfNot()`

- `Void Render(FireworkPlateGroupModel, FireworkPlateGroupViewStyle)`

- `Void RegisterTutorialGo()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Firework
public class FireworkPlateListView : MonoBehaviour, IHotfixable
{
	private SimpleLayoutContent _plateListLeft; // 0x18
	private SimpleLayoutContent _plateListRight; // 0x20
	private GameObject _pnlPlateLocked; // 0x28
	private FireworkPlateSubListView _subListView; // 0x30
	private Image _scrollHandler; // 0x38
	private FireworkPlateGroupModel m_cachedGroupModel; // 0x40
	private FireworkPlateGroupViewStyle m_cachedStyle; // 0x48
	private Adapter m_leftAdapter; // 0x50
	private Adapter m_rightAdapter; // 0x58
	private Boolean m_inited; // 0x60
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x0
	private static DelegateBridge __Hotfix0_Render; // 0x8
	private static DelegateBridge __Hotfix0_RegisterTutorialGo; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18


	// RVA: 0x28f0294 VA: 0x7594f08294
	private Void _InitIfNot() { }
	// RVA: 0x28f0460 VA: 0x7594f08460
	public Void Render(FireworkPlateGroupModel groupModel, FireworkPlateGroupViewStyle style) { }
	// RVA: 0x28f07e8 VA: 0x7594f087e8
	public Void RegisterTutorialGo() { }
	// RVA: 0x28f09d8 VA: 0x7594f089d8
	public Void .ctor() { }
}
```
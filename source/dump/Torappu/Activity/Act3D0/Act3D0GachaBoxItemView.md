# Act3D0GachaBoxItemView

**Namespace:** `Torappu.Activity.Act3D0`


## Fields

- `Text _remainCount`

- `Transform _itemCardContainer`

- `Single _itemScaleFactor`

- `CanvasGroup _canvasGroup`

- `GameObject _outStack`

- `GameObject _replicateFlag`

- `UIItemCard m_itemCard`

- `Tween m_cacheTween`

- `Boolean m_isInited`


## Methods

- `Void _InitIfNot()`

- `Void Render(Act3D0GachaBoxItemInfo)`

- `Void _OnItemCardClicked(Int32)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act3D0
public class Act3D0GachaBoxItemView : MonoBehaviour, IHotfixable
{
	private Text _remainCount; // 0x18
	private Transform _itemCardContainer; // 0x20
	private Single _itemScaleFactor; // 0x28
	private CanvasGroup _canvasGroup; // 0x30
	private GameObject _outStack; // 0x38
	private GameObject _replicateFlag; // 0x40
	private const Single ANIMATION_ALPHA_SPEED; // 0x0
	private const Single ANIMATION_ANIM_SPEED; // 0x0
	private UIItemCard m_itemCard; // 0x48
	private Tween m_cacheTween; // 0x50
	private Boolean m_isInited; // 0x58
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x0
	private static DelegateBridge __Hotfix0_Render; // 0x8
	private static DelegateBridge __Hotfix0__OnItemCardClicked; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18


	// RVA: 0x3233524 VA: 0x759584b524
	private Void _InitIfNot() { }
	// RVA: 0x3232c6c VA: 0x759584ac6c
	public Void Render(Act3D0GachaBoxItemInfo item) { }
	// RVA: 0x3233710 VA: 0x759584b710
	private Void _OnItemCardClicked(Int32 position) { }
	// RVA: 0x3233810 VA: 0x759584b810
	public Void .ctor() { }
}
```
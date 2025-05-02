# SiracusaCharSelectItemView

**Namespace:** `Torappu.UI.SiracusaMap`


## Fields

- `GameObject _objStateHeadActive`

- `UIDynImage _imgHead`

- `GameObject _objCompleteProgress`

- `GameObject _objProgressTxt`

- `Text _txtProgress`

- `GameObject _objCompleteTag`

- `GameObject _objNewChar`

- `GameObject _objStateHeadUnknown`

- `UIDynImage _imgHeadUnknown`

- `GameObject _objHeadSelectedFrame`

- `Boolean m_hasInited`

- `String m_cachedCharId`

- `AutoPackSpriteHub m_charCardSpriteHub`


## Methods

- `Void set_eventCharItemClick(Action`1)`

- `Void _InitIfNot()`

- `String _GetItemIconPath(String)`

- `Void Init(AutoPackSpriteHub)`

- `Void Render(SiracusaCharSelectItemViewModel)`

- `Void OnItemClick()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.SiracusaMap
public class SiracusaCharSelectItemView : MonoBehaviour, IHotfixable
{
	private GameObject _objStateHeadActive; // 0x18
	private UIDynImage _imgHead; // 0x20
	private GameObject _objCompleteProgress; // 0x28
	private GameObject _objProgressTxt; // 0x30
	private Text _txtProgress; // 0x38
	private GameObject _objCompleteTag; // 0x40
	private GameObject _objNewChar; // 0x48
	private GameObject _objStateHeadUnknown; // 0x50
	private UIDynImage _imgHeadUnknown; // 0x58
	private GameObject _objHeadSelectedFrame; // 0x60
	private Boolean m_hasInited; // 0x68
	private String m_cachedCharId; // 0x70
	private const String PROGRESS_TXT; // 0x0
	private AutoPackSpriteHub m_charCardSpriteHub; // 0x78
	private Action`1 <eventCharItemClick>k__BackingField; // 0x80
	private static DelegateBridge __Hotfix0_get_eventCharItemClick; // 0x0
	private static DelegateBridge __Hotfix0_set_eventCharItemClick; // 0x8
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x10
	private static DelegateBridge __Hotfix0__GetItemIconPath; // 0x18
	private static DelegateBridge __Hotfix0_Init; // 0x20
	private static DelegateBridge __Hotfix0_Render; // 0x28
	private static DelegateBridge __Hotfix0_OnItemClick; // 0x30
	private static DelegateBridge _c__Hotfix0_ctor; // 0x38

	public Action`1 eventCharItemClick { get; set; }

	// RVA: 0x23edc88 VA: 0x7594a05c88
	public Action`1 get_eventCharItemClick() { }
	// RVA: 0x23edcf0 VA: 0x7594a05cf0
	public Void set_eventCharItemClick(Action`1 value) { }
	// RVA: 0x23edd74 VA: 0x7594a05d74
	private Void _InitIfNot() { }
	// RVA: 0x23edde8 VA: 0x7594a05de8
	private String _GetItemIconPath(String spriteName) { }
	// RVA: 0x23edec8 VA: 0x7594a05ec8
	public Void Init(AutoPackSpriteHub spriteHub) { }
	// RVA: 0x23edf98 VA: 0x7594a05f98
	public Void Render(SiracusaCharSelectItemViewModel itemViewModel) { }
	// RVA: 0x23ee470 VA: 0x7594a06470
	public Void OnItemClick() { }
	// RVA: 0x23ee520 VA: 0x7594a06520
	public Void .ctor() { }
}
```
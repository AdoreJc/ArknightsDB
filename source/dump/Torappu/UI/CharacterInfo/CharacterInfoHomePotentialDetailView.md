# CharacterInfoHomePotentialDetailView

**Namespace:** `Torappu.UI.CharacterInfo`


## Fields

- `Image _spriteIcon`

- `Single _baseHeight`

- `SimpleLayoutContent _content`

- `Text _detailText`

- `Text _itemName`

- `GameObject _switchPotentialItemGroup`

- `Adapter m_adater`

- `Boolean m_isInited`

- `String m_cacheDetail`

- `TextGenerator m_textGenerate`

- `CharViewModel m_charViewModel`


## Methods

- `Void _InitIfNot()`

- `Void Render(CharViewModel)`

- `Single CalcAndApplyHeight()`

- `Void _ShowPotentialItem(UIItemViewModel)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.CharacterInfo
public class CharacterInfoHomePotentialDetailView : MonoBehaviour, IHotfixable
{
	private Image _spriteIcon; // 0x18
	private Single _baseHeight; // 0x20
	private SimpleLayoutContent _content; // 0x28
	private Text _detailText; // 0x30
	private Text _itemName; // 0x38
	private GameObject _switchPotentialItemGroup; // 0x40
	private Adapter m_adater; // 0x48
	private Boolean m_isInited; // 0x50
	private String m_cacheDetail; // 0x58
	private TextGenerator m_textGenerate; // 0x60
	private CharViewModel m_charViewModel; // 0x68
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x0
	private static DelegateBridge __Hotfix0_Render; // 0x8
	private static DelegateBridge __Hotfix0_CalcAndApplyHeight; // 0x10
	private static DelegateBridge __Hotfix0__ShowPotentialItem; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20


	// RVA: 0x2d7bdac VA: 0x7595393dac
	private Void _InitIfNot() { }
	// RVA: 0x2d7bee8 VA: 0x7595393ee8
	public Void Render(CharViewModel viewModel) { }
	// RVA: 0x2d7c2b0 VA: 0x75953942b0
	public Single CalcAndApplyHeight() { }
	// RVA: 0x2d7c12c VA: 0x759539412c
	private Void _ShowPotentialItem(UIItemViewModel cardModel) { }
	// RVA: 0x2d7c384 VA: 0x7595394384
	public Void .ctor() { }
}
```
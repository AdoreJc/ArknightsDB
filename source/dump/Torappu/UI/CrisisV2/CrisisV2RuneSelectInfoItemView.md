# CrisisV2RuneSelectInfoItemView

**Namespace:** `Torappu.UI.CrisisV2`


## Fields

- `Text _textDesc`

- `UIAtlasImage _imgPoint`

- `Text _textPoint`

- `Color _textColorFocus`

- `Color _textColorUnFocus`

- `Color _textColorPointLow`

- `Color _textColorPointMiddle`

- `Color _textColorPointHigh`

- `GameObject _panelHighLight`

- `TextGenerator m_textGenerator`

- `String m_desc`

- `Single m_descHeight`


## Properties

- `Single preferredHeight`


## Methods

- `Single get_preferredHeight()`

- `Void Render(ICrisisV2RuneSingleItemInfo)`

- `Void SetDescFocusType(Boolean)`

- `CrisisV2RuneSingleItmePointLvType _GetPointLvType(Int32)`

- `Void _RegisterTutorialGo(ICrisisV2RuneSingleItemInfo)`

- `Color _GetPointLvCol(CrisisV2RuneSingleItmePointLvType)`

- `Single _CalcHeight(String)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.CrisisV2
public class CrisisV2RuneSelectInfoItemView : MonoBehaviour, IHotfixable
{
	private Text _textDesc; // 0x18
	private UIAtlasImage _imgPoint; // 0x20
	private Text _textPoint; // 0x28
	private Color _textColorFocus; // 0x30
	private Color _textColorUnFocus; // 0x40
	private Color _textColorPointLow; // 0x50
	private Color _textColorPointMiddle; // 0x60
	private Color _textColorPointHigh; // 0x70
	private GameObject _panelHighLight; // 0x80
	private TextGenerator m_textGenerator; // 0x88
	private String m_desc; // 0x90
	private Single m_descHeight; // 0x98
	private static DelegateBridge __Hotfix0_get_preferredHeight; // 0x0
	private static DelegateBridge __Hotfix0_Render; // 0x8
	private static DelegateBridge __Hotfix0_SetDescFocusType; // 0x10
	private static DelegateBridge __Hotfix0__GetPointLvType; // 0x18
	private static DelegateBridge __Hotfix0__RegisterTutorialGo; // 0x20
	private static DelegateBridge __Hotfix0__GetPointLvCol; // 0x28
	private static DelegateBridge __Hotfix0__CalcHeight; // 0x30
	private static DelegateBridge _c__Hotfix0_ctor; // 0x38

	public Single preferredHeight { get; }

	// RVA: 0x2c14d3c VA: 0x759522cd3c
	public Single get_preferredHeight() { }
	// RVA: 0x2c14ad4 VA: 0x759522cad4
	public Void Render(ICrisisV2RuneSingleItemInfo info) { }
	// RVA: 0x2c151e4 VA: 0x759522d1e4
	public Void SetDescFocusType(Boolean focus) { }
	// RVA: 0x2c14ed4 VA: 0x759522ced4
	private CrisisV2RuneSingleItmePointLvType _GetPointLvType(Int32 point) { }
	// RVA: 0x2c15064 VA: 0x759522d064
	private Void _RegisterTutorialGo(ICrisisV2RuneSingleItemInfo info) { }
	// RVA: 0x2c14fa8 VA: 0x759522cfa8
	private Color _GetPointLvCol(CrisisV2RuneSingleItmePointLvType pointLvType) { }
	// RVA: 0x2c14e28 VA: 0x759522ce28
	private Single _CalcHeight(String desc) { }
	// RVA: 0x2c15294 VA: 0x759522d294
	public Void .ctor() { }
}
```
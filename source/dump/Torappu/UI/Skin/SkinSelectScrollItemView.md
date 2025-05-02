# SkinSelectScrollItemView

**Namespace:** `Torappu.UI.Skin`


## Fields

- `Int32 index`

- `UIAtlasImage _portraitImage`

- `UIAtlasImage _portraitImage2`

- `Text _name`

- `RectTransform _bound`

- `CanvasGroup _alphaBlend`

- `GameObject _content`

- `CanvasGroup _alphaPart`

- `Image _skinGroupIcon`

- `Image _alphaMask`

- `Single _boundPerLenth`

- `SkinSelectPriceViewObj _priceObj`

- `Single sortingIndex`

- `Int32 skinIndex`

- `String skinId`

- `Single m_currentState`

- `Boolean m_isEmpty`


## Methods

- `Void OnClick()`

- `Void ApplyData(SkinSelectViewModel)`

- `Void ApplyState(Single)`

- `Single _ModGetPos(Single)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Skin
public class SkinSelectScrollItemView : MonoBehaviour, IHotfixable
{
	public Int32 index; // 0x18
	private UIAtlasImage _portraitImage; // 0x20
	private UIAtlasImage _portraitImage2; // 0x28
	private Text _name; // 0x30
	private RectTransform _bound; // 0x38
	private CanvasGroup _alphaBlend; // 0x40
	private GameObject _content; // 0x48
	private CanvasGroup _alphaPart; // 0x50
	private Image _skinGroupIcon; // 0x58
	private Image _alphaMask; // 0x60
	private Single _boundPerLenth; // 0x68
	private SkinSelectPriceViewObj _priceObj; // 0x70
	public Single sortingIndex; // 0x78
	public Int32 skinIndex; // 0x7c
	public String skinId; // 0x80
	public Action`1 OnClickEvent; // 0x88
	private Single m_currentState; // 0x90
	private Boolean m_isEmpty; // 0x94
	private static readonly Single[] EFFECT_STATE; // 0x0
	private static DelegateBridge __Hotfix0_OnClick; // 0x8
	private static DelegateBridge __Hotfix0_ApplyData; // 0x10
	private static DelegateBridge __Hotfix0_ApplyState; // 0x18
	private static DelegateBridge __Hotfix0__ModGetPos; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x28


	// RVA: 0x23d6214 VA: 0x75949ee214
	public Void OnClick() { }
	// RVA: 0x23d62b0 VA: 0x75949ee2b0
	public Void ApplyData(SkinSelectViewModel skinViewModel) { }
	// RVA: 0x23d66fc VA: 0x75949ee6fc
	public Void ApplyState(Single state) { }
	// RVA: 0x23d69e8 VA: 0x75949ee9e8
	private Single _ModGetPos(Single state) { }
	// RVA: 0x23d6a94 VA: 0x75949eea94
	public Void .ctor() { }
	// RVA: 0x23d6b58 VA: 0x75949eeb58
	private static Void .cctor() { }
}
```
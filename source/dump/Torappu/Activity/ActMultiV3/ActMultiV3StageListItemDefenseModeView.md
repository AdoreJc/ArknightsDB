# ActMultiV3StageListItemDefenseModeView

**Namespace:** `Torappu.Activity.ActMultiV3`


## Fields

- `UIAtlasObject _atlasObject`

- `String _imgGrayStarSpriteName`

- `String _imgRedStarSpriteName`

- `Text _textExScore`

- `GameObject _pnlLastWave`

- `GameObject _pnlNormal`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.ActMultiV3
public class ActMultiV3StageListItemDefenseModeView : ActMultiV3StageListItemModeView
{
	private UIAtlasImage[] _imgStarList; // 0x18
	private UIAtlasObject _atlasObject; // 0x20
	private String _imgGrayStarSpriteName; // 0x28
	private String _imgRedStarSpriteName; // 0x30
	private Text _textExScore; // 0x38
	private GameObject _pnlLastWave; // 0x40
	private GameObject _pnlNormal; // 0x48
	private static DelegateBridge __Hotfix0_get_modeType; // 0x0
	private static DelegateBridge __Hotfix0_Render; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public override ActMultiV3MapModeType modeType { get; }

	// RVA: 0x314b620 VA: 0x7595763620
	public override ActMultiV3MapModeType get_modeType() { }
	// RVA: 0x314b688 VA: 0x7595763688
	public override Void Render(ActMultiV3StageItemViewModel viewModel) { }
	// RVA: 0x314b894 VA: 0x7595763894
	public Void .ctor() { }
}
```
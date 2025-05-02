# ActMultiV3StageListItemNormalModeView

**Namespace:** `Torappu.Activity.ActMultiV3`


## Fields

- `UIAtlasObject _atlasObject`

- `String _imgGrayStarSpriteName`

- `String _imgRedStarSpriteName`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.ActMultiV3
public class ActMultiV3StageListItemNormalModeView : ActMultiV3StageListItemModeView
{
	private UIAtlasImage[] _imgStarList; // 0x18
	private UIAtlasObject _atlasObject; // 0x20
	private String _imgGrayStarSpriteName; // 0x28
	private String _imgRedStarSpriteName; // 0x30
	private static DelegateBridge __Hotfix0_get_modeType; // 0x0
	private static DelegateBridge __Hotfix0_Render; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public override ActMultiV3MapModeType modeType { get; }

	// RVA: 0x314bb34 VA: 0x7595763b34
	public override ActMultiV3MapModeType get_modeType() { }
	// RVA: 0x314bb9c VA: 0x7595763b9c
	public override Void Render(ActMultiV3StageItemViewModel viewModel) { }
	// RVA: 0x314bd04 VA: 0x7595763d04
	public Void .ctor() { }
}
```
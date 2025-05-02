# NameCardV2MainlineModuleView

**Namespace:** `Torappu.UI.Friend`


## Fields

- `Image _bgImg`

- `Image _chapterTitleBg`

- `Text _chapterEnName`

- `Text _stageCode`

- `TwoStateToggle _stageAllCompleteToggle`


## Methods

- `Void <>xLuaBaseProxy_OnApplyStyle(NameCardV2SkinStyle)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Friend
public class NameCardV2MainlineModuleView : NameCardV2BaseRemovableModuleView`1
{
	private Image _bgImg; // 0xb8
	private Image[] _coloredIcons; // 0xc0
	private Text[] _coloredTexts; // 0xc8
	private Image _chapterTitleBg; // 0xd0
	private Text _chapterEnName; // 0xd8
	private Text _stageCode; // 0xe0
	private TwoStateToggle _stageAllCompleteToggle; // 0xe8
	private static DelegateBridge __Hotfix0_OnModuleViewRendered; // 0x0
	private static DelegateBridge __Hotfix0_OnApplyStyle; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10


	// RVA: 0x28e504c VA: 0x7594efd04c
	public override Void OnModuleViewRendered(NameCardV2MainlineModuleModel model) { }
	// RVA: 0x28e5170 VA: 0x7594efd170
	protected override Void OnApplyStyle(NameCardV2SkinStyle style) { }
	// RVA: 0x28e5324 VA: 0x7594efd324
	public Void .ctor() { }
	// RVA: 0x28e53b4 VA: 0x7594efd3b4
	private Void <>xLuaBaseProxy_OnApplyStyle(NameCardV2SkinStyle P0) { }
}
```
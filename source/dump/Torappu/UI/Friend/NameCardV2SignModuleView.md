# NameCardV2SignModuleView

**Namespace:** `Torappu.UI.Friend`


## Fields

- `Image _bgImg`

- `Text _resumeText`

- `Button _editSignBtn`

- `AudioClickPlayer _editSignAudio`


## Methods

- `Void OnEditClick()`

- `Void <>xLuaBaseProxy_OnApplyStyle(NameCardV2SkinStyle)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Friend
public class NameCardV2SignModuleView : NameCardV2BaseRemovableModuleView`1
{
	private Image _bgImg; // 0xb8
	private Image[] _coloredIcons; // 0xc0
	private Text[] _coloredTexts; // 0xc8
	private Text _resumeText; // 0xd0
	private Button _editSignBtn; // 0xd8
	private AudioClickPlayer _editSignAudio; // 0xe0
	private static DelegateBridge __Hotfix0_OnModuleViewRendered; // 0x0
	private static DelegateBridge __Hotfix0_OnApplyStyle; // 0x8
	private static DelegateBridge __Hotfix0_OnEditClick; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18


	// RVA: 0x28e7414 VA: 0x7594eff414
	public override Void OnModuleViewRendered(NameCardV2SignModuleModel model) { }
	// RVA: 0x28e74e0 VA: 0x7594eff4e0
	protected override Void OnApplyStyle(NameCardV2SkinStyle style) { }
	// RVA: 0x28e7694 VA: 0x7594eff694
	public Void OnEditClick() { }
	// RVA: 0x28e7744 VA: 0x7594eff744
	public Void .ctor() { }
	// RVA: 0x28e77d4 VA: 0x7594eff7d4
	private Void <>xLuaBaseProxy_OnApplyStyle(NameCardV2SkinStyle P0) { }
}
```
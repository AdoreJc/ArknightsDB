# NameCardV2BackgroundModuleView

**Namespace:** `Torappu.UI.Friend`


## Fields

- `Image _bgImg`

- `Image _bgPureColor`

- `Image _leftBorder`

- `Image _rightBorder`

- `Transform _effectHolder`


## Methods

- `Void ClickNamecardBackground()`

- `Void SetUIParticle(GameObject)`

- `Void <>xLuaBaseProxy_OnApplyStyle(NameCardV2SkinStyle)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Friend
public class NameCardV2BackgroundModuleView : NameCardV2BaseFixedModuleView`1
{
	private Image _bgImg; // 0x50
	private Image _bgPureColor; // 0x58
	private Image _leftBorder; // 0x60
	private Image _rightBorder; // 0x68
	private Transform _effectHolder; // 0x70
	private static DelegateBridge __Hotfix0_OnModuleViewRendered; // 0x0
	private static DelegateBridge __Hotfix0_OnApplyStyle; // 0x8
	private static DelegateBridge __Hotfix0_ClickNamecardBackground; // 0x10
	private static DelegateBridge __Hotfix0_SetUIParticle; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20


	// RVA: 0x28e0b90 VA: 0x7594ef8b90
	public override Void OnModuleViewRendered(NameCardV2BackgroundModuleModel model) { }
	// RVA: 0x28e0c08 VA: 0x7594ef8c08
	protected override Void OnApplyStyle(NameCardV2SkinStyle style) { }
	// RVA: 0x28e0f6c VA: 0x7594ef8f6c
	public Void ClickNamecardBackground() { }
	// RVA: 0x28e0e68 VA: 0x7594ef8e68
	private Void SetUIParticle(GameObject mainEffect) { }
	// RVA: 0x28e1128 VA: 0x7594ef9128
	public Void .ctor() { }
	// RVA: 0x28e11b8 VA: 0x7594ef91b8
	private Void <>xLuaBaseProxy_OnApplyStyle(NameCardV2SkinStyle P0) { }
}
```
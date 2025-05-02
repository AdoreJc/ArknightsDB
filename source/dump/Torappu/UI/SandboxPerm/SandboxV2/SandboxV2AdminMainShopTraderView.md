# SandboxV2AdminMainShopTraderView

**Namespace:** `Torappu.UI.SandboxPerm.SandboxV2`


## Fields

- `Text _textName`

- `Text _textDesc`

- `Single _textTweenDuration`

- `Tween m_textTweener`


## Methods

- `Void _PlayTextTween(String)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.SandboxPerm.SandboxV2
public class SandboxV2AdminMainShopTraderView : DataBinder`1, IHotfixable
{
	private Text _textName; // 0x20
	private Text _textDesc; // 0x28
	private Single _textTweenDuration; // 0x30
	private Tween m_textTweener; // 0x38
	private static DelegateBridge __Hotfix0_OnValueChanged; // 0x0
	private static DelegateBridge __Hotfix0__PlayTextTween; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10


	// RVA: 0x24eb5c0 VA: 0x7594b035c0
	public override Void OnValueChanged(SandboxV2AdminMainShopProperty property) { }
	// RVA: 0x24eb688 VA: 0x7594b03688
	private Void _PlayTextTween(String dialog) { }
	// RVA: 0x24eb7ec VA: 0x7594b037ec
	public Void .ctor() { }
}
```
# UnlockCondView

**Namespace:** ` `


## Fields

- `Text _condDesc`

- `Text _textCurrProgress`

- `Text _textTotalProgress`

- `CanvasGroup _canvasIncomplete`

- `Single _alphaCompleted`

- `GameObject _pnlCompleted`


## Methods

- `Void Render(SandboxV2ChallengeModeUnlockCondViewModel)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
private class UnlockCondView : IHotfixable
{
	private const String TOTAL_PROGRESS_FORMAT; // 0x0
	private Text _condDesc; // 0x10
	private Text _textCurrProgress; // 0x18
	private Text _textTotalProgress; // 0x20
	private CanvasGroup _canvasIncomplete; // 0x28
	private Single _alphaCompleted; // 0x30
	private GameObject _pnlCompleted; // 0x38
	private static DelegateBridge __Hotfix0_Render; // 0x0
	private static DelegateBridge _c__Hotfix0_ctor; // 0x8


	// RVA: 0x25d6f10 VA: 0x7594beef10
	public Void Render(SandboxV2ChallengeModeUnlockCondViewModel condViewModel) { }
	// RVA: 0x25d70a8 VA: 0x7594bef0a8
	public Void .ctor() { }
}
```
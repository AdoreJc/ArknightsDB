# SandboxV2HomeChallengeEntryView

**Namespace:** `Torappu.UI.SandboxPerm.SandboxV2`


## Fields

- `GameObject _bkgLocked`

- `GameObject _bkgUnlocked`

- `GameObject _iconInactivated`

- `GameObject _iconLocked`

- `GameObject _inactivatedMask`

- `CanvasGroup _canvasBtn`

- `Single _alphaInactivated`

- `Button _entryBtn`


## Methods

- `Void Render(SandboxV2HomeModel)`

- `GameObject TutorialOnly_GetEntryBtnGo()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.SandboxPerm.SandboxV2
public class SandboxV2HomeChallengeEntryView : MonoBehaviour, IHotfixable
{
	private GameObject _bkgLocked; // 0x18
	private GameObject _bkgUnlocked; // 0x20
	private GameObject _iconInactivated; // 0x28
	private GameObject _iconLocked; // 0x30
	private GameObject _inactivatedMask; // 0x38
	private CanvasGroup _canvasBtn; // 0x40
	private Single _alphaInactivated; // 0x48
	private Button _entryBtn; // 0x50
	private static DelegateBridge __Hotfix0_Render; // 0x0
	private static DelegateBridge __Hotfix0_TutorialOnly_GetEntryBtnGo; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10


	// RVA: 0x25d689c VA: 0x7594bee89c
	public Void Render(SandboxV2HomeModel model) { }
	// RVA: 0x25d6a14 VA: 0x7594beea14
	public GameObject TutorialOnly_GetEntryBtnGo() { }
	// RVA: 0x25d6a88 VA: 0x7594beea88
	public Void .ctor() { }
}
```
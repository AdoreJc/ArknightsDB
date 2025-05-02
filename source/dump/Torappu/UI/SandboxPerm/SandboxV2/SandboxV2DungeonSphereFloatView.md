# SandboxV2DungeonSphereFloatView

**Namespace:** `Torappu.UI.SandboxPerm.SandboxV2`


## Fields

- `GameObject _panelNormal`

- `SandboxV2DungeonSphereNormalView _normalView`

- `GameObject _panelRift`

- `SandboxV2DungeonSphereRiftView _riftView`

- `GameObject _panelChallenge`

- `SandboxV2DungeonSphereChallengeView _challengeView`


## Methods

- `Void Render(SandboxV2DungeonViewModel)`

- `Void TutorialOnly_TryRaiseAVGSignal()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.SandboxPerm.SandboxV2
public class SandboxV2DungeonSphereFloatView : MonoBehaviour, IHotfixable
{
	private GameObject _panelNormal; // 0x18
	private SandboxV2DungeonSphereNormalView _normalView; // 0x20
	private GameObject _panelRift; // 0x28
	private SandboxV2DungeonSphereRiftView _riftView; // 0x30
	private GameObject _panelChallenge; // 0x38
	private SandboxV2DungeonSphereChallengeView _challengeView; // 0x40
	private static DelegateBridge __Hotfix0_Render; // 0x0
	private static DelegateBridge __Hotfix0_TutorialOnly_TryRaiseAVGSignal; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10


	// RVA: 0x255072c VA: 0x7594b6872c
	public Void Render(SandboxV2DungeonViewModel viewModel) { }
	// RVA: 0x2550900 VA: 0x7594b68900
	public Void TutorialOnly_TryRaiseAVGSignal() { }
	// RVA: 0x25513fc VA: 0x7594b693fc
	public Void .ctor() { }
}
```
# SandboxV2DungeonSideBar

**Namespace:** `Torappu.UI.SandboxPerm.SandboxV2`


## Fields

- `UIAnimationLocation _questAnim`

- `UIAnimationLocation _enemyRushAnim`

- `UIAnimationLocation _otherAnim`

- `GameObject _panelEmergencyTrackPoint`

- `Text _enemyRushCount`

- `Text _otherCount`

- `Boolean m_isInited`

- `AnimationSwitchTween m_questTween`

- `AnimationSwitchTween m_enemyRushTween`

- `AnimationSwitchTween m_otherTween`


## Methods

- `Void Render(SandboxV2DungeonViewModel)`

- `Void _InitIfNot()`

- `Builder _GetAnimationSwitchTweenBuilder(UIAnimationLocation)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.SandboxPerm.SandboxV2
public class SandboxV2DungeonSideBar : MonoBehaviour, IHotfixable
{
	private UIAnimationLocation _questAnim; // 0x18
	private UIAnimationLocation _enemyRushAnim; // 0x28
	private UIAnimationLocation _otherAnim; // 0x38
	private GameObject _panelEmergencyTrackPoint; // 0x48
	private Text _enemyRushCount; // 0x50
	private Text _otherCount; // 0x58
	private Boolean m_isInited; // 0x60
	private AnimationSwitchTween m_questTween; // 0x68
	private AnimationSwitchTween m_enemyRushTween; // 0x70
	private AnimationSwitchTween m_otherTween; // 0x78
	private static DelegateBridge __Hotfix0_Render; // 0x0
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x8
	private static DelegateBridge __Hotfix0__GetAnimationSwitchTweenBuilder; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18


	// RVA: 0x255d7e4 VA: 0x7594b757e4
	public Void Render(SandboxV2DungeonViewModel viewModel) { }
	// RVA: 0x255d970 VA: 0x7594b75970
	private Void _InitIfNot() { }
	// RVA: 0x255dae4 VA: 0x7594b75ae4
	private Builder _GetAnimationSwitchTweenBuilder(UIAnimationLocation animLocation) { }
	// RVA: 0x255dbf8 VA: 0x7594b75bf8
	public Void .ctor() { }
}
```
# MeetingTransferStateView

**Namespace:** `Torappu.Building.UI.Meeting`


## Fields

- `Text _visitNumber`

- `Text _socialPointBonus`

- `MeetingClueRestTimeLabel _restTimeLabel`

- `UIAnimationLocation _anim`

- `IMeetingSession m_session`

- `Boolean m_querying`

- `Boolean m_transferComplete`

- `AnimationSwitchTween m_tween`

- `Boolean m_hasInited`

- `Single m_hideTimer`

- `Single m_hideDuration`


## Methods

- `Void _OnTimerExpiredUpdate()`

- `Void Setup(IMeetingSession)`

- `Void OnClick()`

- `Void OnDestroy()`

- `Void _InitIfNot()`

- `Void Update()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Building.UI.Meeting
public class MeetingTransferStateView : MonoBehaviour, IHotfixable
{
	private Text _visitNumber; // 0x18
	private Text _socialPointBonus; // 0x20
	private MeetingClueRestTimeLabel _restTimeLabel; // 0x28
	private UIAnimationLocation _anim; // 0x30
	private IMeetingSession m_session; // 0x40
	private Boolean m_querying; // 0x48
	private Boolean m_transferComplete; // 0x49
	private AnimationSwitchTween m_tween; // 0x50
	private Boolean m_hasInited; // 0x58
	private Single m_hideTimer; // 0x5c
	private Single m_hideDuration; // 0x60
	private static DelegateBridge __Hotfix0__OnTimerExpiredUpdate; // 0x0
	private static DelegateBridge __Hotfix0_Setup; // 0x8
	private static DelegateBridge __Hotfix0_OnClick; // 0x10
	private static DelegateBridge __Hotfix0_OnDestroy; // 0x18
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x20
	private static DelegateBridge __Hotfix0_Update; // 0x28
	private static DelegateBridge _c__Hotfix0_ctor; // 0x30


	// RVA: 0x3dff90c VA: 0x759641790c
	private Void _OnTimerExpiredUpdate() { }
	// RVA: 0x3dff990 VA: 0x7596417990
	public Void Setup(IMeetingSession session) { }
	// RVA: 0x3dffde0 VA: 0x7596417de0
	public Void OnClick() { }
	// RVA: 0x3dffe94 VA: 0x7596417e94
	private Void OnDestroy() { }
	// RVA: 0x3dffccc VA: 0x7596417ccc
	private Void _InitIfNot() { }
	// RVA: 0x3dfff58 VA: 0x7596417f58
	private Void Update() { }
	// RVA: 0x3e00058 VA: 0x7596418058
	public Void .ctor() { }
}
```
# RoguelikeDuelUIBattlePanel

**Namespace:** `Torappu.Battle.Roguelike.Duel`


## Fields

- `UIAnimationLocation _perform`

- `UITextSlider _remainTimeSlider`

- `Text _remainTimeText`

- `GameObject _emergencyMask`

- `Int32 _emergencyTimeThreshold`

- `Int32 m_remainTime`

- `Int32 m_maxTime`

- `RoguelikeDuelUIPlugin m_plugin`

- `RoguelikeDuelGameMode m_gameMode`


## Methods

- `Void InitData(RoguelikeDuelUIPlugin)`

- `Void UpdateData()`

- `Void PlayBattleStartAnimation()`

- `Void _InitUI()`

- `Void _SetRemainTimeInfo()`

- `Void _SetRemainTimeText(Int32)`

- `Void <PlayBattleStartAnimation>b__11_0()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle.Roguelike.Duel
public class RoguelikeDuelUIBattlePanel : MonoBehaviour, IHotfixable
{
	private UIAnimationLocation _perform; // 0x18
	private UITextSlider _remainTimeSlider; // 0x28
	private Text _remainTimeText; // 0x30
	private GameObject _emergencyMask; // 0x38
	private Int32 _emergencyTimeThreshold; // 0x40
	private Int32 m_remainTime; // 0x44
	private Int32 m_maxTime; // 0x48
	private RoguelikeDuelUIPlugin m_plugin; // 0x50
	private RoguelikeDuelGameMode m_gameMode; // 0x58
	private static DelegateBridge __Hotfix0_InitData; // 0x0
	private static DelegateBridge __Hotfix0_UpdateData; // 0x8
	private static DelegateBridge __Hotfix0_PlayBattleStartAnimation; // 0x10
	private static DelegateBridge __Hotfix0__InitUI; // 0x18
	private static DelegateBridge __Hotfix0__SetRemainTimeInfo; // 0x20
	private static DelegateBridge __Hotfix0__SetRemainTimeText; // 0x28
	private static DelegateBridge _c__Hotfix0_ctor; // 0x30


	// RVA: 0x1d4b578 VA: 0x7594363578
	public Void InitData(RoguelikeDuelUIPlugin plugin) { }
	// RVA: 0x1d4b788 VA: 0x7594363788
	public Void UpdateData() { }
	// RVA: 0x1d4bb64 VA: 0x7594363b64
	public Void PlayBattleStartAnimation() { }
	// RVA: 0x1d4b6d0 VA: 0x75943636d0
	private Void _InitUI() { }
	// RVA: 0x1d4b9f8 VA: 0x75943639f8
	private Void _SetRemainTimeInfo() { }
	// RVA: 0x1d4b850 VA: 0x7594363850
	private Void _SetRemainTimeText(Int32 remainTime) { }
	// RVA: 0x1d4bcc8 VA: 0x7594363cc8
	public Void .ctor() { }
	// RVA: 0x1d4bd40 VA: 0x7594363d40
	private Void <PlayBattleStartAnimation>b__11_0() { }
}
```
# RL01TransitionClockView

**Namespace:** `Torappu.UI.Roguelike.RL01`


## Fields

- `UIAtlasImage _imgHourHand`

- `UIAtlasImage _imgMinuteHand`

- `Int32 m_hourRotation`

- `Int32 m_minuteRotation`

- `Boolean m_showClockMove`

- `Tween m_timeRotationTween`


## Methods

- `Tween PlayAnim()`

- `Void Render(RoguelikeGameZoneData)`

- `Void <PlayAnim>b__9_1(Int32)`

- `Void <PlayAnim>b__9_3(Single)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Roguelike.RL01
public class RL01TransitionClockView : MonoBehaviour, IHotfixable
{
	private UIAtlasImage _imgHourHand; // 0x18
	private UIAtlasImage _imgMinuteHand; // 0x20
	private Int32 m_hourRotation; // 0x28
	private Int32 m_minuteRotation; // 0x2c
	private const Single DURATION_PARAM; // 0x0
	private const Single DURATION_PARAM_2; // 0x0
	private const Int32 FRAME_DURATION; // 0x0
	private Boolean m_showClockMove; // 0x30
	private Tween m_timeRotationTween; // 0x38
	private static DelegateBridge __Hotfix0_PlayAnim; // 0x0
	private static DelegateBridge __Hotfix0_Render; // 0x8
	private static DelegateBridge __Hotfix0__GeneHourAndMinute; // 0x10
	private static DelegateBridge __Hotfix0__GetRotationZ; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20


	// RVA: 0x2b7c354 VA: 0x7595194354
	public Tween PlayAnim() { }
	// RVA: 0x2b7ba00 VA: 0x7595193a00
	public Void Render(RoguelikeGameZoneData zoneData) { }
	// RVA: 0x2b7c884 VA: 0x7595194884
	private static Boolean _GeneHourAndMinute(RoguelikeGameZoneData zoneData, out Int32 hourRotation, out Int32 minuteRotation) { }
	// RVA: 0x2b7cab0 VA: 0x7595194ab0
	private static Int32 _GetRotationZ(Int32 target, Int32 total) { }
	// RVA: 0x2b7cb58 VA: 0x7595194b58
	public Void .ctor() { }
	// RVA: 0x2b7cbc8 VA: 0x7595194bc8
	private Void <PlayAnim>b__9_1(Int32 val) { }
	// RVA: 0x2b7cc98 VA: 0x7595194c98
	private Void <PlayAnim>b__9_3(Single val) { }
}
```
# RoguelikeDungeonFloatView

**Namespace:** `Torappu.UI.Roguelike`


## Fields

- `Transform _triggerHolder`

- `UIGuidebookTrigger m_guideBookTrigger`

- `FadeSwitchTween m_switchTween`

- `RoguelikeDungeonZoneViewModel m_cacheZoneModel`

- `UIGuidebookTrigger m_trigger`


## Methods

- `UIGuidebookTrigger _GetGuideBookTrigger()`

- `Void _OnStateEnter(Object)`

- `Void _OnStateResume(Object)`

- `Void Init(RoguelikeDungeonController)`

- `Void SetShow(Boolean, Boolean)`

- `Void <Init>b__12_0()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Roguelike
public class RoguelikeDungeonFloatView : DataBinder`1
{
	private const Single TWEEN_DURATION; // 0x0
	private static readonly Type[] ENABLE_STATES; // 0x0
	private static readonly Type[] IGNORE_STATES; // 0x8
	private Transform _triggerHolder; // 0x20
	private UIGuidebookTrigger m_guideBookTrigger; // 0x28
	private FadeSwitchTween m_switchTween; // 0x30
	private RoguelikeDungeonZoneViewModel m_cacheZoneModel; // 0x38
	private UIGuidebookTrigger m_trigger; // 0x40
	private static DelegateBridge __Hotfix0__GetGuideBookTrigger; // 0x10
	private static DelegateBridge __Hotfix0_OnValueChanged; // 0x18
	private static DelegateBridge __Hotfix0__OnStateEnter; // 0x20
	private static DelegateBridge __Hotfix0__OnStateResume; // 0x28
	private static DelegateBridge __Hotfix0_Init; // 0x30
	private static DelegateBridge __Hotfix0_SetShow; // 0x38
	private static DelegateBridge _c__Hotfix0_ctor; // 0x40


	// RVA: 0x2a0b1ec VA: 0x75950231ec
	private UIGuidebookTrigger _GetGuideBookTrigger() { }
	// RVA: 0x2a0b394 VA: 0x7595023394
	public override Void OnValueChanged(RoguelikeDungeonZoneViewProperty property) { }
	// RVA: 0x2a0b43c VA: 0x759502343c
	private Void _OnStateEnter(Object arg) { }
	// RVA: 0x2a0b650 VA: 0x7595023650
	private Void _OnStateResume(Object arg) { }
	// RVA: 0x2a0b7b4 VA: 0x75950237b4
	public Void Init(RoguelikeDungeonController controller) { }
	// RVA: 0x2a0b598 VA: 0x7595023598
	public Void SetShow(Boolean isShow, Boolean fastMode) { }
	// RVA: 0x2a0bacc VA: 0x7595023acc
	public Void .ctor() { }
	// RVA: 0x2a0bb6c VA: 0x7595023b6c
	private static Void .cctor() { }
	// RVA: 0x2a0bd5c VA: 0x7595023d5c
	private Void <Init>b__12_0() { }
}
```
# Act33SignRedpackViewModel

**Namespace:** `Torappu.Activity.Act33Sign`


## Fields

- `String <activityId>k__BackingField`


## Properties

- `String activityId`

- `Boolean redpackAvailable`


## Methods

- `String get_activityId()`

- `Void set_activityId(String)`

- `Boolean get_redpackAvailable()`

- `Void set_LoadSpriteFromAutoPackHub(Func`3)`

- `Void set_RewardEvent(Action`2)`

- `Sprite _LoadSpriteForCurrentAct(String)`

- `Void LoadData(Int32, List`1, List`1)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act33Sign
public class Act33SignRedpackViewModel : IHotfixable
{
	private List`1 m_itemViewModels; // 0x10
	private Queue`1 m_redpackWaitForSign; // 0x18
	private String <activityId>k__BackingField; // 0x20
	private Func`3 <LoadSpriteFromAutoPackHub>k__BackingField; // 0x28
	private Action`2 <RewardEvent>k__BackingField; // 0x30
	private static DelegateBridge __Hotfix0_get_activityId; // 0x0
	private static DelegateBridge __Hotfix0_set_activityId; // 0x8
	private static DelegateBridge __Hotfix0_get_redpackAvailable; // 0x10
	private static DelegateBridge __Hotfix0_get_redpackItemList; // 0x18
	private static DelegateBridge __Hotfix0_get_LoadSpriteFromAutoPackHub; // 0x20
	private static DelegateBridge __Hotfix0_set_LoadSpriteFromAutoPackHub; // 0x28
	private static DelegateBridge __Hotfix0_get_RewardEvent; // 0x30
	private static DelegateBridge __Hotfix0_set_RewardEvent; // 0x38
	private static DelegateBridge __Hotfix0__LoadSpriteForCurrentAct; // 0x40
	private static DelegateBridge __Hotfix0_LoadData; // 0x48
	private static DelegateBridge _c__Hotfix0_ctor; // 0x50

	public String activityId { get; set; }
	public Boolean redpackAvailable { get; }
	public List`1 redpackItemList { get; }
	public Func`3 LoadSpriteFromAutoPackHub { get; set; }
	public Action`2 RewardEvent { get; set; }

	// RVA: 0x3256ee4 VA: 0x759586eee4
	public String get_activityId() { }
	// RVA: 0x3254138 VA: 0x759586c138
	public Void set_activityId(String value) { }
	// RVA: 0x325480c VA: 0x759586c80c
	public Boolean get_redpackAvailable() { }
	// RVA: 0x3254b84 VA: 0x759586cb84
	public List`1 get_redpackItemList() { }
	// RVA: 0x3256f4c VA: 0x759586ef4c
	public Func`3 get_LoadSpriteFromAutoPackHub() { }
	// RVA: 0x3254518 VA: 0x759586c518
	public Void set_LoadSpriteFromAutoPackHub(Func`3 value) { }
	// RVA: 0x32561c8 VA: 0x759586e1c8
	public Action`2 get_RewardEvent() { }
	// RVA: 0x325459c VA: 0x759586c59c
	public Void set_RewardEvent(Action`2 value) { }
	// RVA: 0x3256fb4 VA: 0x759586efb4
	private Sprite _LoadSpriteForCurrentAct(String spriteId) { }
	// RVA: 0x32541bc VA: 0x759586c1bc
	public Void LoadData(Int32 signCount, List`1 extraHistory, List`1 extraCheckInInfos) { }
	// RVA: 0x3254024 VA: 0x759586c024
	public Void .ctor() { }
}
```
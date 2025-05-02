# CommonFriendAssistViewModel

**Namespace:** `Torappu.UI.CommonFriendAssist`


## Fields

- `String <tips>k__BackingField`

- `ProfessionCategory <profFilter>k__BackingField`


## Properties

- `String tips`

- `ProfessionCategory profFilter`


## Methods

- `String get_tips()`

- `Void set_tips(String)`

- `ProfessionCategory get_profFilter()`

- `Void set_profFilter(ProfessionCategory)`

- `Void set_profTabList(List`1)`

- `Void set_friendAssistList(List`1)`

- `Void Init(ICommonFriendAssistPlugin)`

- `Void Update(CommonFriendAssistData)`

- `Void Clear()`

- `Boolean SetProfFilter(ProfessionCategory)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.CommonFriendAssist
public class CommonFriendAssistViewModel : IHotfixable
{
	private String <tips>k__BackingField; // 0x10
	private ProfessionCategory <profFilter>k__BackingField; // 0x18
	private List`1 <profTabList>k__BackingField; // 0x20
	private List`1 <friendAssistList>k__BackingField; // 0x28
	private static DelegateBridge __Hotfix0_get_tips; // 0x0
	private static DelegateBridge __Hotfix0_set_tips; // 0x8
	private static DelegateBridge __Hotfix0_get_profFilter; // 0x10
	private static DelegateBridge __Hotfix0_set_profFilter; // 0x18
	private static DelegateBridge __Hotfix0_get_profTabList; // 0x20
	private static DelegateBridge __Hotfix0_set_profTabList; // 0x28
	private static DelegateBridge __Hotfix0_get_friendAssistList; // 0x30
	private static DelegateBridge __Hotfix0_set_friendAssistList; // 0x38
	private static DelegateBridge __Hotfix0_Init; // 0x40
	private static DelegateBridge __Hotfix0_Update; // 0x48
	private static DelegateBridge __Hotfix0_Clear; // 0x50
	private static DelegateBridge __Hotfix0_SetProfFilter; // 0x58
	private static DelegateBridge _c__Hotfix0_ctor; // 0x60

	public String tips { get; set; }
	public ProfessionCategory profFilter { get; set; }
	public List`1 profTabList { get; set; }
	public List`1 friendAssistList { get; set; }

	// RVA: 0x2c4ab9c VA: 0x7595262b9c
	public String get_tips() { }
	// RVA: 0x2c4ac04 VA: 0x7595262c04
	private Void set_tips(String value) { }
	// RVA: 0x2c49850 VA: 0x7595261850
	public ProfessionCategory get_profFilter() { }
	// RVA: 0x2c4ac88 VA: 0x7595262c88
	private Void set_profFilter(ProfessionCategory value) { }
	// RVA: 0x2c4ad04 VA: 0x7595262d04
	public List`1 get_profTabList() { }
	// RVA: 0x2c4ad6c VA: 0x7595262d6c
	private Void set_profTabList(List`1 value) { }
	// RVA: 0x2c4adf0 VA: 0x7595262df0
	public List`1 get_friendAssistList() { }
	// RVA: 0x2c4ae58 VA: 0x7595262e58
	private Void set_friendAssistList(List`1 value) { }
	// RVA: 0x2c49488 VA: 0x7595261488
	public Void Init(ICommonFriendAssistPlugin plugin) { }
	// RVA: 0x2c499a4 VA: 0x75952619a4
	public Void Update(CommonFriendAssistData data) { }
	// RVA: 0x2c4902c VA: 0x759526102c
	public Void Clear() { }
	// RVA: 0x2c4a274 VA: 0x7595262274
	public Boolean SetProfFilter(ProfessionCategory profFilter) { }
	// RVA: 0x2c4aeec VA: 0x7595262eec
	public Void .ctor() { }
}
```
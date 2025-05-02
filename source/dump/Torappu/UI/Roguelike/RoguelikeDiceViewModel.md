# RoguelikeDiceViewModel

**Namespace:** `Torappu.UI.Roguelike`


## Fields

- `String <topicId>k__BackingField`

- `RoguelikeDiceModelType <diceType>k__BackingField`

- `Type <typeOfPlugin>k__BackingField`

- `Int32 <dicePoints>k__BackingField`

- `Int32 <canRerollCnt>k__BackingField`

- `RoguelikeDiceRuleData <ruleData>k__BackingField`

- `RoguelikeDiceResultViewModel <result>k__BackingField`


## Properties

- `String topicId`

- `RoguelikeDiceModelType diceType`

- `Type typeOfPlugin`

- `Int32 dicePoints`

- `Int32 canRerollCnt`

- `RoguelikeDiceRuleData ruleData`

- `RoguelikeDiceResultViewModel result`


## Methods

- `String get_topicId()`

- `Void set_topicId(String)`

- `RoguelikeDiceModelType get_diceType()`

- `Void set_diceType(RoguelikeDiceModelType)`

- `Type get_typeOfPlugin()`

- `Void set_typeOfPlugin(Type)`

- `Int32 get_dicePoints()`

- `Void set_dicePoints(Int32)`

- `Int32 get_canRerollCnt()`

- `Void set_canRerollCnt(Int32)`

- `RoguelikeDiceRuleData get_ruleData()`

- `Void set_ruleData(RoguelikeDiceRuleData)`

- `RoguelikeDiceResultViewModel get_result()`

- `Void set_result(RoguelikeDiceResultViewModel)`

- `Void Init(String, Type, Dictionary`2)`

- `Boolean LoadResult()`

- `RoguelikeDiceResultViewModel _LoadResult(Result, RoguelikeDiceRuleData)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Roguelike
public class RoguelikeDiceViewModel : IHotfixable
{
	private String <topicId>k__BackingField; // 0x10
	private RoguelikeDiceModelType <diceType>k__BackingField; // 0x18
	private Type <typeOfPlugin>k__BackingField; // 0x20
	private Int32 <dicePoints>k__BackingField; // 0x28
	private Int32 <canRerollCnt>k__BackingField; // 0x2c
	private RoguelikeDiceRuleData <ruleData>k__BackingField; // 0x30
	private RoguelikeDiceResultViewModel <result>k__BackingField; // 0x38
	private Dictionary`2 m_resultViewModelCreators; // 0x40
	private static DelegateBridge __Hotfix0_get_topicId; // 0x0
	private static DelegateBridge __Hotfix0_set_topicId; // 0x8
	private static DelegateBridge __Hotfix0_get_diceType; // 0x10
	private static DelegateBridge __Hotfix0_set_diceType; // 0x18
	private static DelegateBridge __Hotfix0_get_typeOfPlugin; // 0x20
	private static DelegateBridge __Hotfix0_set_typeOfPlugin; // 0x28
	private static DelegateBridge __Hotfix0_get_dicePoints; // 0x30
	private static DelegateBridge __Hotfix0_set_dicePoints; // 0x38
	private static DelegateBridge __Hotfix0_get_canRerollCnt; // 0x40
	private static DelegateBridge __Hotfix0_set_canRerollCnt; // 0x48
	private static DelegateBridge __Hotfix0_get_ruleData; // 0x50
	private static DelegateBridge __Hotfix0_set_ruleData; // 0x58
	private static DelegateBridge __Hotfix0_get_result; // 0x60
	private static DelegateBridge __Hotfix0_set_result; // 0x68
	private static DelegateBridge __Hotfix0_Init; // 0x70
	private static DelegateBridge __Hotfix0_LoadResult; // 0x78
	private static DelegateBridge __Hotfix0__LoadResult; // 0x80
	private static DelegateBridge _c__Hotfix0_ctor; // 0x88

	public String topicId { get; set; }
	public RoguelikeDiceModelType diceType { get; set; }
	public Type typeOfPlugin { get; set; }
	public Int32 dicePoints { get; set; }
	public Int32 canRerollCnt { get; set; }
	public RoguelikeDiceRuleData ruleData { get; set; }
	public RoguelikeDiceResultViewModel result { get; set; }

	// RVA: 0x29fb0a4 VA: 0x75950130a4
	public String get_topicId() { }
	// RVA: 0x29fb10c VA: 0x759501310c
	private Void set_topicId(String value) { }
	// RVA: 0x29fae0c VA: 0x7595012e0c
	public RoguelikeDiceModelType get_diceType() { }
	// RVA: 0x29fb190 VA: 0x7595013190
	private Void set_diceType(RoguelikeDiceModelType value) { }
	// RVA: 0x29fb20c VA: 0x759501320c
	public Type get_typeOfPlugin() { }
	// RVA: 0x29fb274 VA: 0x7595013274
	private Void set_typeOfPlugin(Type value) { }
	// RVA: 0x29fada4 VA: 0x7595012da4
	public Int32 get_dicePoints() { }
	// RVA: 0x29fb2f8 VA: 0x75950132f8
	private Void set_dicePoints(Int32 value) { }
	// RVA: 0x29fa47c VA: 0x759501247c
	public Int32 get_canRerollCnt() { }
	// RVA: 0x29fb374 VA: 0x7595013374
	private Void set_canRerollCnt(Int32 value) { }
	// RVA: 0x29fad3c VA: 0x7595012d3c
	public RoguelikeDiceRuleData get_ruleData() { }
	// RVA: 0x29fb3f0 VA: 0x75950133f0
	private Void set_ruleData(RoguelikeDiceRuleData value) { }
	// RVA: 0x29fae74 VA: 0x7595012e74
	public RoguelikeDiceResultViewModel get_result() { }
	// RVA: 0x29fb474 VA: 0x7595013474
	private Void set_result(RoguelikeDiceResultViewModel value) { }
	// RVA: 0x29f99cc VA: 0x75950119cc
	public Void Init(String topic, Type pluginType, Dictionary`2 resultViewModelCreators) { }
	// RVA: 0x29f9c64 VA: 0x7595011c64
	public Boolean LoadResult() { }
	// RVA: 0x29fb4f8 VA: 0x75950134f8
	private RoguelikeDiceResultViewModel _LoadResult(Result result, RoguelikeDiceRuleData data) { }
	// RVA: 0x29fb5fc VA: 0x75950135fc
	public Void .ctor() { }
}
```
# RoguelikeTopicEndingCommonViewModel

**Namespace:** `Torappu.UI.RoguelikeTopic`


## Fields

- `String <currTopicId>k__BackingField`

- `GameSettleOuterInfo <settleData>k__BackingField`


## Properties

- `String currTopicId`

- `GameSettleOuterInfo settleData`


## Methods

- `String get_currTopicId()`

- `Void set_currTopicId(String)`

- `GameSettleOuterInfo get_settleData()`

- `Void set_settleData(GameSettleOuterInfo)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.RoguelikeTopic
public class RoguelikeTopicEndingCommonViewModel : RoguelikeTopicEndingViewModelBase, IHotfixable
{
	private String <currTopicId>k__BackingField; // 0x20
	private GameSettleOuterInfo <settleData>k__BackingField; // 0x28
	private static DelegateBridge __Hotfix0_get_currTopicId; // 0x0
	private static DelegateBridge __Hotfix0_set_currTopicId; // 0x8
	private static DelegateBridge __Hotfix0_get_settleData; // 0x10
	private static DelegateBridge __Hotfix0_set_settleData; // 0x18
	private static DelegateBridge __Hotfix0_LoadData; // 0x20
	private static DelegateBridge __Hotfix0_CompleteCurrShow; // 0x28
	private static DelegateBridge _c__Hotfix0_ctor; // 0x30

	public String currTopicId { get; set; }
	public GameSettleOuterInfo settleData { get; set; }

	// RVA: 0x264e3c0 VA: 0x7594c663c0
	public String get_currTopicId() { }
	// RVA: 0x264e428 VA: 0x7594c66428
	private Void set_currTopicId(String value) { }
	// RVA: 0x264e4ac VA: 0x7594c664ac
	public GameSettleOuterInfo get_settleData() { }
	// RVA: 0x264e514 VA: 0x7594c66514
	private Void set_settleData(GameSettleOuterInfo value) { }
	// RVA: 0x264e598 VA: 0x7594c66598
	public override Void LoadData(String topicId, SettleInfo settleInfo) { }
	// RVA: 0x264e6e8 VA: 0x7594c666e8
	public override Boolean CompleteCurrShow() { }
	// RVA: 0x264db3c VA: 0x7594c65b3c
	public Void .ctor() { }
}
```
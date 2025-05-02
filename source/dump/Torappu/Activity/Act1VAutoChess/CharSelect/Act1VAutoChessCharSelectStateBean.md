# Act1VAutoChessCharSelectStateBean

**Namespace:** `Torappu.Activity.Act1VAutoChess.CharSelect`


## Fields

- `InputParam m_param`

- `TemplateCharSelectMainProperty m_property`

- `Act1VAutoChessCharShopChessData m_forChess`


## Properties

- `TemplateCharSelectMainProperty property`

- `InputParam inputParam`


## Methods

- `TemplateCharSelectMainProperty get_property()`

- `Void SetInputData(InputParam)`

- `InputParam get_inputParam()`

- `TemplateCharSelectCardViewModel CreateCardViewModel(Int32, TemplateCharSelectCharInputData, PlayerCharacter)`

- `DIYInfo _CheckInChess(PlayerCharacter, String, ActivityAutoChessVerify1Data)`

- `String _TryGetInitialEquip(PlayerCharacter)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act1VAutoChess.CharSelect
public class Act1VAutoChessCharSelectStateBean : IStateBean, IHotfixable
{
	private InputParam m_param; // 0x10
	private TemplateCharSelectMainProperty m_property; // 0x18
	private Act1VAutoChessCharShopChessData m_forChess; // 0x20
	private Dictionary`2 m_diyChess; // 0x28
	private static DelegateBridge __Hotfix0_get_property; // 0x0
	private static DelegateBridge __Hotfix0_SetInputData; // 0x8
	private static DelegateBridge __Hotfix0_get_inputParam; // 0x10
	private static DelegateBridge __Hotfix0_CreateCardViewModel; // 0x18
	private static DelegateBridge __Hotfix0__CheckInChess; // 0x20
	private static DelegateBridge __Hotfix0__TryGetInitialEquip; // 0x28
	private static DelegateBridge _c__Hotfix0_ctor; // 0x30

	public TemplateCharSelectMainProperty property { get; }
	public InputParam inputParam { get; }

	// RVA: 0x338dac8 VA: 0x75959a5ac8
	public TemplateCharSelectMainProperty get_property() { }
	// RVA: 0x338e3a4 VA: 0x75959a63a4
	public Void SetInputData(InputParam inputParam) { }
	// RVA: 0x338dfe4 VA: 0x75959a5fe4
	public InputParam get_inputParam() { }
	// RVA: 0x338e4e8 VA: 0x75959a64e8
	public TemplateCharSelectCardViewModel CreateCardViewModel(Int32 instId, TemplateCharSelectCharInputData inputNullable, PlayerCharacter playerData) { }
	// RVA: 0x338e7cc VA: 0x75959a67cc
	private DIYInfo _CheckInChess(PlayerCharacter playerData, String actId, ActivityAutoChessVerify1Data actData) { }
	// RVA: 0x338ecf0 VA: 0x75959a6cf0
	private String _TryGetInitialEquip(PlayerCharacter playerChar) { }
	// RVA: 0x338e2e4 VA: 0x75959a62e4
	public Void .ctor() { }
}
```
# SandboxV2AdminMainModel

**Namespace:** `Torappu.UI.SandboxPerm.SandboxV2`


## Fields

- `String <topicId>k__BackingField`

- `Boolean <singleMode>k__BackingField`

- `SandboxV2AdminMainPanelType <currShowType>k__BackingField`

- `Int32 <resumeTick>k__BackingField`


## Properties

- `String topicId`

- `Boolean singleMode`

- `SandboxV2AdminMainPanelType currShowType`

- `Int32 resumeTick`


## Methods

- `String get_topicId()`

- `Void set_topicId(String)`

- `Boolean get_singleMode()`

- `Void set_singleMode(Boolean)`

- `SandboxV2AdminMainPanelType get_currShowType()`

- `Void set_currShowType(SandboxV2AdminMainPanelType)`

- `Int32 get_resumeTick()`

- `Void set_resumeTick(Int32)`

- `Void Init(String, Boolean)`

- `Boolean SetShowPanelType(SandboxV2AdminMainPanelType)`

- `Void MarkResume()`

- `Void SetTabPanelInfo(SandboxV2AdminMainPanelType, TabPanelConfig)`

- `TabPanelConfig GetTabPanelInfo(SandboxV2AdminMainPanelType)`

- `Void RefreshPanelActiveState()`

- `Boolean CheckPanelActive(SandboxV2AdminMainPanelType)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.SandboxPerm.SandboxV2
public class SandboxV2AdminMainModel : IHotfixable
{
	private String <topicId>k__BackingField; // 0x10
	private Boolean <singleMode>k__BackingField; // 0x18
	private SandboxV2AdminMainPanelType <currShowType>k__BackingField; // 0x1c
	private Dictionary`2 m_tabPanelInfos; // 0x20
	private Dictionary`2 m_tabPanelActive; // 0x28
	private Int32 <resumeTick>k__BackingField; // 0x30
	private static DelegateBridge __Hotfix0_get_topicId; // 0x0
	private static DelegateBridge __Hotfix0_set_topicId; // 0x8
	private static DelegateBridge __Hotfix0_get_singleMode; // 0x10
	private static DelegateBridge __Hotfix0_set_singleMode; // 0x18
	private static DelegateBridge __Hotfix0_get_currShowType; // 0x20
	private static DelegateBridge __Hotfix0_set_currShowType; // 0x28
	private static DelegateBridge __Hotfix0_get_resumeTick; // 0x30
	private static DelegateBridge __Hotfix0_set_resumeTick; // 0x38
	private static DelegateBridge __Hotfix0_Init; // 0x40
	private static DelegateBridge __Hotfix0_SetShowPanelType; // 0x48
	private static DelegateBridge __Hotfix0_MarkResume; // 0x50
	private static DelegateBridge __Hotfix0_SetTabPanelInfo; // 0x58
	private static DelegateBridge __Hotfix0_GetTabPanelInfo; // 0x60
	private static DelegateBridge __Hotfix0_RefreshPanelActiveState; // 0x68
	private static DelegateBridge __Hotfix0_CheckPanelActive; // 0x70
	private static DelegateBridge _c__Hotfix0_ctor; // 0x78

	public String topicId { get; set; }
	public Boolean singleMode { get; set; }
	public SandboxV2AdminMainPanelType currShowType { get; set; }
	public Int32 resumeTick { get; set; }

	// RVA: 0x24d9bf4 VA: 0x7594af1bf4
	public String get_topicId() { }
	// RVA: 0x24d9c5c VA: 0x7594af1c5c
	private Void set_topicId(String value) { }
	// RVA: 0x24d8b80 VA: 0x7594af0b80
	public Boolean get_singleMode() { }
	// RVA: 0x24d9ce0 VA: 0x7594af1ce0
	private Void set_singleMode(Boolean value) { }
	// RVA: 0x24d8ef8 VA: 0x7594af0ef8
	public SandboxV2AdminMainPanelType get_currShowType() { }
	// RVA: 0x24d9d60 VA: 0x7594af1d60
	private Void set_currShowType(SandboxV2AdminMainPanelType value) { }
	// RVA: 0x24d9ddc VA: 0x7594af1ddc
	public Int32 get_resumeTick() { }
	// RVA: 0x24d9e44 VA: 0x7594af1e44
	private Void set_resumeTick(Int32 value) { }
	// RVA: 0x24d9ec0 VA: 0x7594af1ec0
	public Void Init(String topic, Boolean single) { }
	// RVA: 0x24d9f54 VA: 0x7594af1f54
	public Boolean SetShowPanelType(SandboxV2AdminMainPanelType panelType) { }
	// RVA: 0x24d9ff4 VA: 0x7594af1ff4
	public Void MarkResume() { }
	// RVA: 0x24da068 VA: 0x7594af2068
	public Void SetTabPanelInfo(SandboxV2AdminMainPanelType panelType, TabPanelConfig config) { }
	// RVA: 0x24d8f60 VA: 0x7594af0f60
	public TabPanelConfig GetTabPanelInfo(SandboxV2AdminMainPanelType panelType) { }
	// RVA: 0x24da248 VA: 0x7594af2248
	public Void RefreshPanelActiveState() { }
	// RVA: 0x24d8d6c VA: 0x7594af0d6c
	public Boolean CheckPanelActive(SandboxV2AdminMainPanelType panelType) { }
	// RVA: 0x24da2d8 VA: 0x7594af22d8
	public Void .ctor() { }
}
```
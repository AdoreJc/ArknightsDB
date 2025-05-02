# SandboxV2RacerInfoPage

**Namespace:** `Torappu.UI.SandboxPerm.SandboxV2`


## Fields

- `RectTransform _dialogContainer`

- `String m_nodeId`

- `String m_topicId`

- `String m_stageId`

- `Int32 m_apCost`

- `Type m_type`

- `UICompDialogMgr m_dialogMgr`


## Properties

- `String topicId`

- `Type type`

- `String nodeId`

- `String stageId`

- `Int32 apCost`

- `UICompDialogMgr dialogMgr`


## Methods

- `String get_topicId()`

- `Type get_type()`

- `String get_nodeId()`

- `String get_stageId()`

- `Int32 get_apCost()`

- `UICompDialogMgr get_dialogMgr()`

- `IEnumerator <>n__0()`

- `Void <>xLuaBaseProxy_OnCreate(DataBundle)`

- `IEnumerator <>xLuaBaseProxy_InitStateEngine()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.SandboxPerm.SandboxV2
public class SandboxV2RacerInfoPage : StateEnginePage, ISandboxV2DialogHolder, IHotfixable
{
	private RectTransform _dialogContainer; // 0xe8
	private String m_nodeId; // 0xf0
	private String m_topicId; // 0xf8
	private String m_stageId; // 0x100
	private Int32 m_apCost; // 0x108
	private Type m_type; // 0x10c
	private UICompDialogMgr m_dialogMgr; // 0x110
	private static DelegateBridge __Hotfix0_get_topicId; // 0x0
	private static DelegateBridge __Hotfix0_get_type; // 0x8
	private static DelegateBridge __Hotfix0_get_nodeId; // 0x10
	private static DelegateBridge __Hotfix0_get_stageId; // 0x18
	private static DelegateBridge __Hotfix0_get_apCost; // 0x20
	private static DelegateBridge __Hotfix0_OnCreate; // 0x28
	private static DelegateBridge __Hotfix0_InitStateEngine; // 0x30
	private static DelegateBridge __Hotfix0_get_dialogMgr; // 0x38
	private static DelegateBridge __Hotfix0_CreateCommonTopMenu; // 0x40
	private static DelegateBridge _c__Hotfix0_ctor; // 0x48

	public String topicId { get; }
	public Type type { get; }
	public String nodeId { get; }
	public String stageId { get; }
	public Int32 apCost { get; }
	public UICompDialogMgr dialogMgr { get; }

	// RVA: 0x25e275c VA: 0x7594bfa75c
	public String get_topicId() { }
	// RVA: 0x25e280c VA: 0x7594bfa80c
	public Type get_type() { }
	// RVA: 0x25e28ac VA: 0x7594bfa8ac
	public String get_nodeId() { }
	// RVA: 0x25e295c VA: 0x7594bfa95c
	public String get_stageId() { }
	// RVA: 0x25e2a0c VA: 0x7594bfaa0c
	public Int32 get_apCost() { }
	// RVA: 0x25e8de8 VA: 0x7594c00de8
	protected override Void OnCreate(DataBundle savedInst) { }
	// RVA: 0x25e8ea4 VA: 0x7594c00ea4
	protected override IEnumerator InitStateEngine() { }
	// RVA: 0x25e8f78 VA: 0x7594c00f78
	public UICompDialogMgr get_dialogMgr() { }
	// RVA: 0x25e8fe0 VA: 0x7594c00fe0
	public static CommonTopMenu CreateCommonTopMenu(Transform container, Action onBackClick) { }
	// RVA: 0x25e9118 VA: 0x7594c01118
	public Void .ctor() { }
	// RVA: 0x25e9190 VA: 0x7594c01190
	private IEnumerator <>n__0() { }
	// RVA: 0x25e9198 VA: 0x7594c01198
	private Void <>xLuaBaseProxy_OnCreate(DataBundle P0) { }
	// RVA: 0x25e91a0 VA: 0x7594c011a0
	private IEnumerator <>xLuaBaseProxy_InitStateEngine() { }
}
```
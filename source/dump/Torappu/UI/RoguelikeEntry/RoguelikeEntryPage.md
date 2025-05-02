# RoguelikeEntryPage

**Namespace:** `Torappu.UI.RoguelikeEntry`


## Fields

- `String m_topicIdFromSavedInst`

- `String m_bgmInstIdAlias`


## Properties

- `String topicIdOnOpen`


## Methods

- `String get_topicIdOnOpen()`

- `Void TriggerBGMSignal(String)`

- `String GetBgmInstIdAlias()`

- `Int64 _GetBGMInstId()`

- `Void _ClearBGM()`

- `IEnumerator <>n__0()`

- `Void <>xLuaBaseProxy_OnCreate(DataBundle)`

- `Void <>xLuaBaseProxy_OnStart()`

- `IEnumerator <>xLuaBaseProxy_InitStateEngine()`

- `Void <>xLuaBaseProxy_OnDestroy()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.RoguelikeEntry
public class RoguelikeEntryPage : StateEnginePage, IHotfixable
{
	private UICommonPageEffectHolder[] _effectHolders; // 0xe8
	private String m_topicIdFromSavedInst; // 0xf0
	private String m_bgmInstIdAlias; // 0xf8
	private static DelegateBridge __Hotfix0_get_topicIdOnOpen; // 0x0
	private static DelegateBridge __Hotfix0_OnCreate; // 0x8
	private static DelegateBridge __Hotfix0_OnStart; // 0x10
	private static DelegateBridge __Hotfix0_InitStateEngine; // 0x18
	private static DelegateBridge __Hotfix0_OnDestroy; // 0x20
	private static DelegateBridge __Hotfix0_TriggerBGMSignal; // 0x28
	private static DelegateBridge __Hotfix0_GetBgmInstIdAlias; // 0x30
	private static DelegateBridge __Hotfix0__GetBGMInstId; // 0x38
	private static DelegateBridge __Hotfix0__ClearBGM; // 0x40
	private static DelegateBridge __Hotfix0_CreateCommonTopMenu; // 0x48
	private static DelegateBridge _c__Hotfix0_ctor; // 0x50

	public String topicIdOnOpen { get; }

	// RVA: 0x262cf14 VA: 0x7594c44f14
	public String get_topicIdOnOpen() { }
	// RVA: 0x262cfa8 VA: 0x7594c44fa8
	protected override Void OnCreate(DataBundle savedInst) { }
	// RVA: 0x262d14c VA: 0x7594c4514c
	protected override Void OnStart() { }
	// RVA: 0x262d424 VA: 0x7594c45424
	protected override IEnumerator InitStateEngine() { }
	// RVA: 0x262d4f8 VA: 0x7594c454f8
	protected override Void OnDestroy() { }
	// RVA: 0x262d214 VA: 0x7594c45214
	public Void TriggerBGMSignal(String topicId) { }
	// RVA: 0x262d6b4 VA: 0x7594c456b4
	public String GetBgmInstIdAlias() { }
	// RVA: 0x262d614 VA: 0x7594c45614
	private Int64 _GetBGMInstId() { }
	// RVA: 0x262d56c VA: 0x7594c4556c
	private Void _ClearBGM() { }
	// RVA: 0x262d71c VA: 0x7594c4571c
	public static CommonTopMenu CreateCommonTopMenu(Transform container, Action onBackClick) { }
	// RVA: 0x262d894 VA: 0x7594c45894
	public Void .ctor() { }
	// RVA: 0x262d904 VA: 0x7594c45904
	private IEnumerator <>n__0() { }
	// RVA: 0x262d90c VA: 0x7594c4590c
	private Void <>xLuaBaseProxy_OnCreate(DataBundle P0) { }
	// RVA: 0x262d914 VA: 0x7594c45914
	private Void <>xLuaBaseProxy_OnStart() { }
	// RVA: 0x262d91c VA: 0x7594c4591c
	private IEnumerator <>xLuaBaseProxy_InitStateEngine() { }
	// RVA: 0x262d924 VA: 0x7594c45924
	private Void <>xLuaBaseProxy_OnDestroy() { }
}
```
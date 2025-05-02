# SandboxV2DungeonCrossDayPage

**Namespace:** `Torappu.UI.SandboxPerm.SandboxV2`


## Fields

- `RectTransform _dialogContainer`

- `Boolean m_initReadArchive`

- `Boolean m_initRiftSettle`

- `Boolean m_initChallengeSettle`

- `Coroutine m_tutorialCoroutine`

- `UICompDialogMgr m_dialogMgr`


## Properties

- `String topicId`

- `Boolean needShowSettleCalc`

- `SandboxV2DungeonReadArchiveType readArchiveType`

- `UICompDialogMgr dialogMgr`


## Methods

- `String get_topicId()`

- `Boolean get_needShowSettleCalc()`

- `SandboxV2DungeonReadArchiveType get_readArchiveType()`

- `UICompDialogMgr get_dialogMgr()`

- `Void _TutorialOnly_RaiseAVGSignal()`

- `Void _StopTutorialCoroutine()`

- `IEnumerator _WaitAndRaiseSignal()`

- `IEnumerator <>n__0()`

- `Void <>xLuaBaseProxy_OnCreate(DataBundle)`

- `Void <>xLuaBaseProxy_OnStart()`

- `Void <>xLuaBaseProxy_OnStop()`

- `IEnumerator <>xLuaBaseProxy_InitStateEngine()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.SandboxPerm.SandboxV2
public class SandboxV2DungeonCrossDayPage : StateEnginePage
{
	private RectTransform _dialogContainer; // 0xe8
	private Boolean m_initReadArchive; // 0xf0
	private Boolean m_initRiftSettle; // 0xf1
	private Boolean m_initChallengeSettle; // 0xf2
	private Coroutine m_tutorialCoroutine; // 0xf8
	private UICompDialogMgr m_dialogMgr; // 0x100
	private static DelegateBridge __Hotfix0_get_topicId; // 0x0
	private static DelegateBridge __Hotfix0_get_needShowSettleCalc; // 0x8
	private static DelegateBridge __Hotfix0_get_readArchiveType; // 0x10
	private static DelegateBridge __Hotfix0_get_dialogMgr; // 0x18
	private static DelegateBridge __Hotfix0_OnCreate; // 0x20
	private static DelegateBridge __Hotfix0_OnStart; // 0x28
	private static DelegateBridge __Hotfix0_OnStop; // 0x30
	private static DelegateBridge __Hotfix0_InitStateEngine; // 0x38
	private static DelegateBridge __Hotfix0__TutorialOnly_RaiseAVGSignal; // 0x40
	private static DelegateBridge __Hotfix0__StopTutorialCoroutine; // 0x48
	private static DelegateBridge __Hotfix0__WaitAndRaiseSignal; // 0x50
	private static DelegateBridge _c__Hotfix0_ctor; // 0x58

	public String topicId { get; }
	public Boolean needShowSettleCalc { get; }
	public SandboxV2DungeonReadArchiveType readArchiveType { get; }
	public UICompDialogMgr dialogMgr { get; }

	// RVA: 0x25194b0 VA: 0x7594b314b0
	public String get_topicId() { }
	// RVA: 0x2521218 VA: 0x7594b39218
	public Boolean get_needShowSettleCalc() { }
	// RVA: 0x25212ac VA: 0x7594b392ac
	public SandboxV2DungeonReadArchiveType get_readArchiveType() { }
	// RVA: 0x2521338 VA: 0x7594b39338
	public UICompDialogMgr get_dialogMgr() { }
	// RVA: 0x25213a0 VA: 0x7594b393a0
	protected override Void OnCreate(DataBundle savedInst) { }
	// RVA: 0x252145c VA: 0x7594b3945c
	protected override Void OnStart() { }
	// RVA: 0x2521638 VA: 0x7594b39638
	protected override Void OnStop() { }
	// RVA: 0x252172c VA: 0x7594b3972c
	protected override IEnumerator InitStateEngine() { }
	// RVA: 0x252155c VA: 0x7594b3955c
	private Void _TutorialOnly_RaiseAVGSignal() { }
	// RVA: 0x25216ac VA: 0x7594b396ac
	private Void _StopTutorialCoroutine() { }
	// RVA: 0x2521800 VA: 0x7594b39800
	private IEnumerator _WaitAndRaiseSignal() { }
	// RVA: 0x25218c4 VA: 0x7594b398c4
	public Void .ctor() { }
	// RVA: 0x2521934 VA: 0x7594b39934
	private IEnumerator <>n__0() { }
	// RVA: 0x252193c VA: 0x7594b3993c
	private Void <>xLuaBaseProxy_OnCreate(DataBundle P0) { }
	// RVA: 0x2521944 VA: 0x7594b39944
	private Void <>xLuaBaseProxy_OnStart() { }
	// RVA: 0x252194c VA: 0x7594b3994c
	private Void <>xLuaBaseProxy_OnStop() { }
	// RVA: 0x2521954 VA: 0x7594b39954
	private IEnumerator <>xLuaBaseProxy_InitStateEngine() { }
}
```
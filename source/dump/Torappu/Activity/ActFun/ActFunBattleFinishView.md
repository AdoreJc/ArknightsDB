# ActFunBattleFinishView

**Namespace:** `Torappu.Activity.ActFun`


## Fields

- `String _mainDialog`

- `RectTransform _dlgRoot`

- `String _actfunActId`

- `LuaUIContext m_context`


## Properties

- `Transform root`

- `String mainDialog`


## Methods

- `T LoadAsset(String)`

- `Void UnloadAsset(Object)`

- `Void OnLeaveContext()`

- `Void EventOnExitClick()`

- `Transform get_root()`

- `String get_mainDialog()`

- `IEnumerator <>xLuaBaseProxy_ShowEnterEffectCoroutine()`

- `String <>xLuaBaseProxy_OverriddenActId(String, String)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.ActFun
public class ActFunBattleFinishView : ActivityBattleFinishView, IContextHost
{
	private const String ACTID_ACTFUN; // 0x0
	private String _mainDialog; // 0x30
	private RectTransform _dlgRoot; // 0x38
	private String _actfunActId; // 0x40
	private LuaUIContext m_context; // 0x48
	private static DelegateBridge __Hotfix0_OnInit; // 0x0
	private static DelegateBridge __Hotfix0_ShowEnterEffectCoroutine; // 0x8
	private static DelegateBridge __Hotfix0_OverriddenActId; // 0x10
	private static DelegateBridge __Hotfix0_LoadAsset; // 0x18
	private static DelegateBridge __Hotfix0_UnloadAsset; // 0x20
	private static DelegateBridge __Hotfix0_OnLeaveContext; // 0x28
	private static DelegateBridge __Hotfix0_EventOnExitClick; // 0x30
	private static DelegateBridge __Hotfix0_get_root; // 0x38
	private static DelegateBridge __Hotfix0_get_mainDialog; // 0x40
	private static DelegateBridge __Hotfix0_CompDeclaration; // 0x48
	private static DelegateBridge _c__Hotfix0_ctor; // 0x50

	public Transform root { get; }
	public String mainDialog { get; }

	// RVA: 0x319a014 VA: 0x75957b2014
	protected override Void OnInit() { }
	// RVA: 0x319a168 VA: 0x75957b2168
	public override IEnumerator ShowEnterEffectCoroutine() { }
	// RVA: 0x319a23c VA: 0x75957b223c
	protected override String OverriddenActId(String rawActId, String assetPath) { }
	// RVA: 0x VA: 0x0
	public T LoadAsset(String path) { }
	// RVA: 0x319a368 VA: 0x75957b2368
	public Void UnloadAsset(Object asset) { }
	// RVA: 0x319a410 VA: 0x75957b2410
	public Void OnLeaveContext() { }
	// RVA: 0x319a474 VA: 0x75957b2474
	public Void EventOnExitClick() { }
	// RVA: 0x319a4d8 VA: 0x75957b24d8
	public Transform get_root() { }
	// RVA: 0x319a590 VA: 0x75957b2590
	public String get_mainDialog() { }
	// RVA: 0x319a5f8 VA: 0x75957b25f8
	public IDictionary`2 CompDeclaration() { }
	// RVA: 0x319a65c VA: 0x75957b265c
	public Void .ctor() { }
	// RVA: 0x319a6cc VA: 0x75957b26cc
	private IEnumerator <>xLuaBaseProxy_ShowEnterEffectCoroutine() { }
	// RVA: 0x319a6d4 VA: 0x75957b26d4
	private String <>xLuaBaseProxy_OverriddenActId(String P0, String P1) { }
}
```
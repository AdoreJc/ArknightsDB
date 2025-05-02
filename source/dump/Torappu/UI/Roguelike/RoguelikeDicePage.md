# RoguelikeDicePage

**Namespace:** `Torappu.UI.Roguelike`


## Fields

- `Transform _viewRoot`

- `Transform _pluginRoot`

- `Transform _diceSceneRoot`

- `RoguelikeDiceView m_view`

- `RoguelikeDicePlugin m_plugin`

- `RoguelikeDiceModelProperty m_prop`


## Methods

- `Void _InitIfNot()`

- `Void _EventOnComplete()`

- `Void _EventOnReroll()`

- `Void _ReqChoice(Choice, Action)`

- `Void <_EventOnComplete>b__10_0()`

- `Void <_EventOnReroll>b__11_0()`

- `Void <>xLuaBaseProxy_OnCreate(DataBundle)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Roguelike
public class RoguelikeDicePage : UIPage
{
	private Transform _viewRoot; // 0xd0
	private Transform _pluginRoot; // 0xd8
	private Transform _diceSceneRoot; // 0xe0
	private RoguelikeDiceView m_view; // 0xe8
	private RoguelikeDicePlugin m_plugin; // 0xf0
	private RoguelikeDiceModelProperty m_prop; // 0xf8
	private static DelegateBridge __Hotfix0_Open; // 0x0
	private static DelegateBridge __Hotfix0_OnCreate; // 0x8
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x10
	private static DelegateBridge __Hotfix0__EventOnComplete; // 0x18
	private static DelegateBridge __Hotfix0__EventOnReroll; // 0x20
	private static DelegateBridge __Hotfix0__ReqChoice; // 0x28
	private static DelegateBridge _c__Hotfix0_ctor; // 0x30


	// RVA: 0x VA: 0x0
	public static Void Open(String topicId) { }
	// RVA: 0x29f9004 VA: 0x7595011004
	protected override Void OnCreate(DataBundle savedInst) { }
	// RVA: 0x29f9080 VA: 0x7595011080
	private Void _InitIfNot() { }
	// RVA: 0x29f9fe4 VA: 0x7595011fe4
	private Void _EventOnComplete() { }
	// RVA: 0x29fa380 VA: 0x7595012380
	private Void _EventOnReroll() { }
	// RVA: 0x29fa128 VA: 0x7595012128
	private Void _ReqChoice(Choice aChoice, Action callback) { }
	// RVA: 0x29fa4ec VA: 0x75950124ec
	public Void .ctor() { }
	// RVA: 0x29fa604 VA: 0x7595012604
	private Void <_EventOnComplete>b__10_0() { }
	// RVA: 0x29fa60c VA: 0x759501260c
	private Void <_EventOnReroll>b__11_0() { }
	// RVA: 0x29fa698 VA: 0x7595012698
	private Void <>xLuaBaseProxy_OnCreate(DataBundle P0) { }
}
```
# BuildingTrainPage

**Namespace:** `Torappu.Building.UI.Train`


## Fields

- `PrefabInstHolder _topMenuHolder`


## Methods

- `Void _ReturnPage()`

- `Void _OnInitTopMenu(GameObject)`

- `Void OnMessage(Int32, ValueBundle)`

- `IEnumerator _ResetToDefaultStateCoroutine()`

- `Void <_OnInitTopMenu>b__4_0()`

- `Void <>xLuaBaseProxy_OnCreate(DataBundle)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Building.UI.Train
public class BuildingTrainPage : BuildingCommonPage, IValueMsgReceiver
{
	public const Int32 MSG_TRAINEE_INVALID; // 0x0
	private PrefabInstHolder _topMenuHolder; // 0x110
	private static DelegateBridge __Hotfix0__ReturnPage; // 0x0
	private static DelegateBridge __Hotfix0_OnCreate; // 0x8
	private static DelegateBridge __Hotfix0__OnInitTopMenu; // 0x10
	private static DelegateBridge __Hotfix0_OnMessage; // 0x18
	private static DelegateBridge __Hotfix0__ResetToDefaultStateCoroutine; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x28


	// RVA: 0x3d777c4 VA: 0x759638f7c4
	private Void _ReturnPage() { }
	// RVA: 0x3d77874 VA: 0x759638f874
	protected override Void OnCreate(DataBundle savedInst) { }
	// RVA: 0x3d7795c VA: 0x759638f95c
	private Void _OnInitTopMenu(GameObject inst) { }
	// RVA: 0x3d77ab0 VA: 0x759638fab0
	public Void OnMessage(Int32 msg, ValueBundle param) { }
	// RVA: 0x3d77b74 VA: 0x759638fb74
	private IEnumerator _ResetToDefaultStateCoroutine() { }
	// RVA: 0x3d77c48 VA: 0x759638fc48
	public Void .ctor() { }
	// RVA: 0x3d77cb8 VA: 0x759638fcb8
	private Void <_OnInitTopMenu>b__4_0() { }
	// RVA: 0x3d77cbc VA: 0x759638fcbc
	private Void <>xLuaBaseProxy_OnCreate(DataBundle P0) { }
}
```
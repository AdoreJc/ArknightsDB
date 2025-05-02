# ACEAntiDataSDK

**Namespace:** `Torappu.SDK.AntiData`


## Methods

- `Void <>xLuaBaseProxy_OnEnterGame()`


## Dump
```C#
// Dll : Torappu.Common.dll
// Namespace : Torappu.SDK.AntiData
public class ACEAntiDataSDK : ServiceAntiDataSDK
{
	private const String NON_PROD_UID_FORMAT; // 0x0
	private static __XLua_Gen_Delegate1 __Hotfix0_OnEnterGame; // 0x0
	private static __XLua_Gen_Delegate131 __Hotfix0_GetData1; // 0x8
	private static __XLua_Gen_Delegate131 __Hotfix0_GetData2; // 0x10
	private static __XLua_Gen_Delegate5 __Hotfix0_IsEnabled; // 0x18
	private static __XLua_Gen_Delegate8 __Hotfix0_IsData4Supported; // 0x20
	private static __XLua_Gen_Delegate1 __Hotfix0_StartScanData4; // 0x28
	private static __XLua_Gen_Delegate132 __Hotfix0_CheckData4; // 0x30
	private static __XLua_Gen_Delegate133 __Hotfix0_GetData4; // 0x38
	private static __XLua_Gen_Delegate1 _c__Hotfix0_ctor; // 0x40


	// RVA: 0x67925cc VA: 0x7598daa5cc
	protected override Void OnEnterGame() { }
	// RVA: 0x679272c VA: 0x7598daa72c
	protected override Byte[] GetData1() { }
	// RVA: 0x67927cc VA: 0x7598daa7cc
	protected override Byte[] GetData2() { }
	// RVA: 0x6790600 VA: 0x7598da8600
	public static Boolean IsEnabled() { }
	// RVA: 0x679286c VA: 0x7598daa86c
	protected override Boolean IsData4Supported() { }
	// RVA: 0x67928d8 VA: 0x7598daa8d8
	protected override Void StartScanData4() { }
	// RVA: 0x6792960 VA: 0x7598daa960
	protected override Boolean CheckData4(UInt32 token) { }
	// RVA: 0x67929f4 VA: 0x7598daa9f4
	protected override Byte[] GetData4(UInt32 token) { }
	// RVA: 0x67906a8 VA: 0x7598da86a8
	public Void .ctor() { }
	// RVA: 0x6792ac0 VA: 0x7598daaac0
	private Void <>xLuaBaseProxy_OnEnterGame() { }
}
```
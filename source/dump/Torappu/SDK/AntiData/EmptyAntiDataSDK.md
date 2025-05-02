# EmptyAntiDataSDK

**Namespace:** `Torappu.SDK.AntiData`


## Fields

- `Double m_dataReadyTs`


## Methods

- `Void _EditorOnlyData4Supported(ref)`

- `Void _EditorOnlyStartScan()`

- `Void _EditorOnlyCheckData4(ref)`

- `Void _EditorOnlyGetData4(UInt32, ref)`


## Dump
```C#
// Dll : Torappu.Common.dll
// Namespace : Torappu.SDK.AntiData
public class EmptyAntiDataSDK : ServiceAntiDataSDK
{
	private Double m_dataReadyTs; // 0x48
	private static __XLua_Gen_Delegate131 __Hotfix0_GetData1; // 0x0
	private static __XLua_Gen_Delegate131 __Hotfix0_GetData2; // 0x8
	private static __XLua_Gen_Delegate8 __Hotfix0_IsData4Supported; // 0x10
	private static __XLua_Gen_Delegate1 __Hotfix0_StartScanData4; // 0x18
	private static __XLua_Gen_Delegate132 __Hotfix0_CheckData4; // 0x20
	private static __XLua_Gen_Delegate133 __Hotfix0_GetData4; // 0x28
	private static __XLua_Gen_Delegate134 __Hotfix0__EditorOnlyMockBytes; // 0x30
	private static __XLua_Gen_Delegate135 __Hotfix0__EditorOnlyData4Supported; // 0x38
	private static __XLua_Gen_Delegate1 __Hotfix0__EditorOnlyStartScan; // 0x40
	private static __XLua_Gen_Delegate135 __Hotfix0__EditorOnlyCheckData4; // 0x48
	private static __XLua_Gen_Delegate136 __Hotfix0__EditorOnlyGetData4; // 0x50
	private static __XLua_Gen_Delegate1 _c__Hotfix0_ctor; // 0x58


	// RVA: 0x6792ac4 VA: 0x7598daaac4
	protected override Byte[] GetData1() { }
	// RVA: 0x6792b34 VA: 0x7598daab34
	protected override Byte[] GetData2() { }
	// RVA: 0x6792ba4 VA: 0x7598daaba4
	protected override Boolean IsData4Supported() { }
	// RVA: 0x6792c14 VA: 0x7598daac14
	protected override Void StartScanData4() { }
	// RVA: 0x6792c80 VA: 0x7598daac80
	protected override Boolean CheckData4(UInt32 token) { }
	// RVA: 0x6792d04 VA: 0x7598daad04
	protected override Byte[] GetData4(UInt32 token) { }
	// RVA: 0x6792d88 VA: 0x7598daad88
	private static Void _EditorOnlyMockBytes(ref Byte[] data, Single prob, Int32 minLen, Int32 maxLen, Boolean alphaBetaOnly) { }
	// RVA: 0x6792e38 VA: 0x7598daae38
	private Void _EditorOnlyData4Supported(ref Boolean enable) { }
	// RVA: 0x6792ec0 VA: 0x7598daaec0
	private Void _EditorOnlyStartScan() { }
	// RVA: 0x6792f2c VA: 0x7598daaf2c
	private Void _EditorOnlyCheckData4(ref Boolean ready) { }
	// RVA: 0x6793028 VA: 0x7598dab028
	private Void _EditorOnlyGetData4(UInt32 token, ref Byte[] data) { }
	// RVA: 0x6790740 VA: 0x7598da8740
	public Void .ctor() { }
}
```
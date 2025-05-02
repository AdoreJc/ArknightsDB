# SDKGameBI

**Namespace:** `Torappu.SDK`


## Methods

- `Void U8Login()`

- `Void GSLogin()`

- `Void StartGame()`

- `Void StopGame()`

- `Void SysInit()`

- `Void _SetData(Int32, Object)`

- `String _LoadDeviceSoC()`

- `String _LoadDeviceGraphicsName()`

- `Void _LoadEmulatorAndVersion(out, out)`

- `Boolean _LoadIsIOSAppOnMac()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.SDK
public class SDKGameBI : Singleton`1
{
	private static DelegateBridge _c__Hotfix0_ctor; // 0x0
	private static DelegateBridge __Hotfix0_U8Login; // 0x8
	private static DelegateBridge __Hotfix0_GSLogin; // 0x10
	private static DelegateBridge __Hotfix0_StartGame; // 0x18
	private static DelegateBridge __Hotfix0_StopGame; // 0x20
	private static DelegateBridge __Hotfix0_SysInit; // 0x28
	private static DelegateBridge __Hotfix0__IsSysEnabled; // 0x30
	private static DelegateBridge __Hotfix0__SetData; // 0x38
	private static DelegateBridge __Hotfix0__LoadDeviceSoC; // 0x40
	private static DelegateBridge __Hotfix0__LoadDeviceGraphicsName; // 0x48
	private static DelegateBridge __Hotfix0__LoadEmulatorAndVersion; // 0x50
	private static DelegateBridge __Hotfix0__LoadIsIOSAppOnMac; // 0x58


	// RVA: 0x357ba7c VA: 0x7595b93a7c
	private Void .ctor() { }
	// RVA: 0x357bb0c VA: 0x7595b93b0c
	public Void U8Login() { }
	// RVA: 0x357bd64 VA: 0x7595b93d64
	public Void GSLogin() { }
	// RVA: 0x357be70 VA: 0x7595b93e70
	public Void StartGame() { }
	// RVA: 0x357bee0 VA: 0x7595b93ee0
	public Void StopGame() { }
	// RVA: 0x357bf50 VA: 0x7595b93f50
	public Void SysInit() { }
	// RVA: 0x357c2dc VA: 0x7595b942dc
	private static Boolean _IsSysEnabled() { }
	// RVA: 0x357bbdc VA: 0x7595b93bdc
	private Void _SetData(Int32 data, Object param) { }
	// RVA: 0x357c0d4 VA: 0x7595b940d4
	private String _LoadDeviceSoC() { }
	// RVA: 0x357c048 VA: 0x7595b94048
	private String _LoadDeviceGraphicsName() { }
	// RVA: 0x357c19c VA: 0x7595b9419c
	private Void _LoadEmulatorAndVersion(out String emulator, out String version) { }
	// RVA: 0x357c138 VA: 0x7595b94138
	private Boolean _LoadIsIOSAppOnMac() { }
}
```
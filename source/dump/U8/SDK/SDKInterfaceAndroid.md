# SDKInterfaceAndroid

**Namespace:** `U8.SDK`


## Fields

- `AndroidJavaObject jo`

- `String packageName`

- `AndroidJavaObject packageInfo`


## Methods

- `T SDKCall(String, Object[])`

- `Void SDKCall(String, Object[])`


## Dump
```C#
// Dll : U8SDK.dll
// Namespace : U8.SDK
public class SDKInterfaceAndroid : U8SDKInterface
{
	private AndroidJavaObject jo; // 0xc0
	private String packageName; // 0xc8
	private AndroidJavaObject packageInfo; // 0xd0


	// RVA: 0x67ddb60 VA: 0x7598df5b60
	public Void .ctor() { }
	// RVA: 0x VA: 0x0
	private T SDKCall(String method, Object[] param) { }
	// RVA: 0x67e396c VA: 0x7598dfb96c
	private Void SDKCall(String method, Object[] param) { }
	// RVA: 0x67e3904 VA: 0x7598dfb904
	private static AndroidJavaObject CallMethodObj(AndroidJavaObject obj, String methodName, Object[] param) { }
	// RVA: 0x67e37f0 VA: 0x7598dfb7f0
	private static Object CallMethodString(AndroidJavaObject obj, String methodName, Boolean isBytes, Object[] param) { }
	// RVA: 0x67e3a24 VA: 0x7598dfba24
	private static AndroidJavaObject CallMethodStatic(String className, String methodName, Object[] param) { }
	// RVA: 0x67e363c VA: 0x7598dfb63c
	private static AndroidJavaObject GetItemStatic(String className, String fieldName) { }
	// RVA: 0x67e3c64 VA: 0x7598dfbc64
	private static AndroidJavaObject GetItemObj(AndroidJavaObject obj, String fieldName) { }
	// RVA: 0x67e3cbc VA: 0x7598dfbcbc
	protected override String LoadExtraConfig() { }
	// RVA: 0x67e3d70 VA: 0x7598dfbd70
	protected override Void V2Init(String env) { }
	// RVA: 0x67e3d7c VA: 0x7598dfbd7c
	protected override Void Init() { }
	// RVA: 0x67e3e18 VA: 0x7598dfbe18
	protected override Void Login() { }
	// RVA: 0x67e3eb4 VA: 0x7598dfbeb4
	protected override Void LoginCustom(String customData) { }
	// RVA: 0x67e3f78 VA: 0x7598dfbf78
	protected override Void SwitchLogin() { }
	// RVA: 0x67e4014 VA: 0x7598dfc014
	protected override Boolean Logout() { }
	// RVA: 0x67e40b8 VA: 0x7598dfc0b8
	public override Boolean ShowAccountCenter() { }
	// RVA: 0x67e415c VA: 0x7598dfc15c
	public override Void SubmitGameData(U8ExtraGameData data) { }
	// RVA: 0x67e42d8 VA: 0x7598dfc2d8
	public override Boolean SDKExit() { }
	// RVA: 0x67e439c VA: 0x7598dfc39c
	protected override Void Pay(U8PayParams data) { }
	// RVA: 0x67e4470 VA: 0x7598dfc470
	public override Boolean IsSupportLogin() { }
	// RVA: 0x67e4524 VA: 0x7598dfc524
	public override Boolean IsSupportExit() { }
	// RVA: 0x67e45d8 VA: 0x7598dfc5d8
	public override Boolean IsSupportAccountCenter() { }
	// RVA: 0x67e468c VA: 0x7598dfc68c
	public override Boolean IsSupportLogout() { }
	// RVA: 0x67e4740 VA: 0x7598dfc740
	public override Void SetData(Int32 type, String paramJson) { }
	// RVA: 0x67e4870 VA: 0x7598dfc870
	public override String GetData(Int32 type, String paramJson) { }
	// RVA: 0x67e49b8 VA: 0x7598dfc9b8
	protected override SDKMeta LoadSDKMeta() { }
	// RVA: 0x67e4de8 VA: 0x7598dfcde8
	protected override Boolean IsNativePlugin() { }
}
```
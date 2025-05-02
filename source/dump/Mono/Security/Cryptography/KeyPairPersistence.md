# KeyPairPersistence

**Namespace:** `Mono.Security.Cryptography`


## Fields

- `CspParameters _params`

- `String _keyvalue`

- `String _filename`

- `String _container`


## Properties

- `String Filename`

- `String KeyValue`

- `CspParameters Parameters`

- `Boolean CanChange`

- `Boolean UseDefaultKeyContainer`

- `Boolean UseMachineKeyStore`

- `String ContainerName`


## Methods

- `String get_Filename()`

- `String get_KeyValue()`

- `Void set_KeyValue(String)`

- `CspParameters get_Parameters()`

- `Boolean Load()`

- `Void Save()`

- `Void Remove()`

- `Boolean get_CanChange()`

- `Boolean get_UseDefaultKeyContainer()`

- `Boolean get_UseMachineKeyStore()`

- `String get_ContainerName()`

- `CspParameters Copy(CspParameters)`

- `Void FromXml(String)`

- `String ToXml()`


## Dump
```C#
// Dll : mscorlib.dll
// Namespace : Mono.Security.Cryptography
internal class KeyPairPersistence
{
	private static Boolean _userPathExists; // 0x0
	private static String _userPath; // 0x8
	private static Boolean _machinePathExists; // 0x10
	private static String _machinePath; // 0x18
	private CspParameters _params; // 0x10
	private String _keyvalue; // 0x18
	private String _filename; // 0x20
	private String _container; // 0x28
	private static Object lockobj; // 0x20

	public String Filename { get; }
	public String KeyValue { get; set; }
	public CspParameters Parameters { get; }
	private static String UserPath { get; }
	private static String MachinePath { get; }
	private Boolean CanChange { get; }
	private Boolean UseDefaultKeyContainer { get; }
	private Boolean UseMachineKeyStore { get; }
	private String ContainerName { get; }

	// RVA: 0x5f0bc90 VA: 0x7598523c90
	public Void .ctor(CspParameters parameters) { }
	// RVA: 0x5f0bc98 VA: 0x7598523c98
	public Void .ctor(CspParameters parameters, String keyPair) { }
	// RVA: 0x5f0bdcc VA: 0x7598523dcc
	public String get_Filename() { }
	// RVA: 0x5f0ccb4 VA: 0x7598524cb4
	public String get_KeyValue() { }
	// RVA: 0x5f0ccbc VA: 0x7598524cbc
	public Void set_KeyValue(String value) { }
	// RVA: 0x5f0cce0 VA: 0x7598524ce0
	public CspParameters get_Parameters() { }
	// RVA: 0x5f0cce8 VA: 0x7598524ce8
	public Boolean Load() { }
	// RVA: 0x5f0cfd0 VA: 0x7598524fd0
	public Void Save() { }
	// RVA: 0x5f0d550 VA: 0x7598525550
	public Void Remove() { }
	// RVA: 0x5f0c6f4 VA: 0x75985246f4
	private static String get_UserPath() { }
	// RVA: 0x5f0c134 VA: 0x7598524134
	private static String get_MachinePath() { }
	// RVA: 0x5f0d6c8 VA: 0x75985256c8
	internal static Boolean _CanSecure(Char* root) { }
	// RVA: 0x5f0d6cc VA: 0x75985256cc
	internal static Boolean _ProtectUser(Char* path) { }
	// RVA: 0x5f0d6d0 VA: 0x75985256d0
	internal static Boolean _ProtectMachine(Char* path) { }
	// RVA: 0x5f0d6d4 VA: 0x75985256d4
	internal static Boolean _IsUserProtected(Char* path) { }
	// RVA: 0x5f0d6d8 VA: 0x75985256d8
	internal static Boolean _IsMachineProtected(Char* path) { }
	// RVA: 0x5f0d6dc VA: 0x75985256dc
	private static Boolean CanSecure(String path) { }
	// RVA: 0x5f0d4c0 VA: 0x75985254c0
	private static Boolean ProtectUser(String path) { }
	// RVA: 0x5f0d430 VA: 0x7598525430
	private static Boolean ProtectMachine(String path) { }
	// RVA: 0x5f0d5a8 VA: 0x75985255a8
	private static Boolean IsUserProtected(String path) { }
	// RVA: 0x5f0d638 VA: 0x7598525638
	private static Boolean IsMachineProtected(String path) { }
	// RVA: 0x5f0ccd0 VA: 0x7598524cd0
	private Boolean get_CanChange() { }
	// RVA: 0x5f0d77c VA: 0x759852577c
	private Boolean get_UseDefaultKeyContainer() { }
	// RVA: 0x5f0c114 VA: 0x7598524114
	private Boolean get_UseMachineKeyStore() { }
	// RVA: 0x5f0bfa0 VA: 0x7598523fa0
	private String get_ContainerName() { }
	// RVA: 0x5f0bd34 VA: 0x7598523d34
	private CspParameters Copy(CspParameters p) { }
	// RVA: 0x5f0ce98 VA: 0x7598524e98
	private Void FromXml(String xml) { }
	// RVA: 0x5f0d21c VA: 0x759852521c
	private String ToXml() { }
	// RVA: 0x5f0d7a0 VA: 0x75985257a0
	private static Void .cctor() { }
}
```
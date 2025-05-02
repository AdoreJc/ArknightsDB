# Object

**Namespace:** `UnityEngine`


## Fields

- `IntPtr m_CachedPtr`


## Properties

- `String name`

- `HideFlags hideFlags`


## Methods

- `Int32 GetInstanceID()`

- `Void EnsureRunningOnMainThread()`

- `IntPtr GetCachedPtr()`

- `String get_name()`

- `Void set_name(String)`

- `HideFlags get_hideFlags()`

- `Void set_hideFlags(HideFlags)`


## Dump
```C#
// Dll : UnityEngine.CoreModule.dll
// Namespace : UnityEngine
public class Object
{
	private IntPtr m_CachedPtr; // 0x10
	internal static Int32 OffsetOfInstanceIDInCPlusPlusObject; // 0x0
	private const String objectIsNullMessage; // 0x0
	private const String cloneDestroyedMessage; // 0x0

	public String name { get; set; }
	public HideFlags hideFlags { get; set; }

	// RVA: 0x68882c4 VA: 0x7598ea02c4
	public Int32 GetInstanceID() { }
	// RVA: 0x6888420 VA: 0x7598ea0420
	public override Int32 GetHashCode() { }
	// RVA: 0x6888428 VA: 0x7598ea0428
	public override Boolean Equals(Object other) { }
	// RVA: 0x6888628 VA: 0x7598ea0628
	public static Boolean op_Implicit(Object exists) { }
	// RVA: 0x6888588 VA: 0x7598ea0588
	private static Boolean CompareBaseObjects(Object lhs, Object rhs) { }
	// RVA: 0x68886e8 VA: 0x7598ea06e8
	private Void EnsureRunningOnMainThread() { }
	// RVA: 0x688868c VA: 0x7598ea068c
	private static Boolean IsNativeObjectAlive(Object o) { }
	// RVA: 0x68887d0 VA: 0x7598ea07d0
	private IntPtr GetCachedPtr() { }
	// RVA: 0x68887d8 VA: 0x7598ea07d8
	public String get_name() { }
	// RVA: 0x6888888 VA: 0x7598ea0888
	public Void set_name(String value) { }
	// RVA: 0x6888950 VA: 0x7598ea0950
	public static Object Instantiate(Object original, Vector3 position, Quaternion rotation) { }
	// RVA: 0x6888bf4 VA: 0x7598ea0bf4
	public static Object Instantiate(Object original, Vector3 position, Quaternion rotation, Transform parent) { }
	// RVA: 0x6888e44 VA: 0x7598ea0e44
	public static Object Instantiate(Object original) { }
	// RVA: 0x6888f74 VA: 0x7598ea0f74
	public static Object Instantiate(Object original, Transform parent) { }
	// RVA: 0x6888fdc VA: 0x7598ea0fdc
	public static Object Instantiate(Object original, Transform parent, Boolean instantiateInWorldSpace) { }
	// RVA: 0x VA: 0x0
	public static T Instantiate(T original) { }
	// RVA: 0x VA: 0x0
	public static T Instantiate(T original, Vector3 position, Quaternion rotation) { }
	// RVA: 0x VA: 0x0
	public static T Instantiate(T original, Vector3 position, Quaternion rotation, Transform parent) { }
	// RVA: 0x VA: 0x0
	public static T Instantiate(T original, Transform parent) { }
	// RVA: 0x VA: 0x0
	public static T Instantiate(T original, Transform parent, Boolean worldPositionStays) { }
	// RVA: 0x688917c VA: 0x7598ea117c
	public static Void Destroy(Object obj, Single t) { }
	// RVA: 0x68891c8 VA: 0x7598ea11c8
	public static Void Destroy(Object obj) { }
	// RVA: 0x6889240 VA: 0x7598ea1240
	public static Void DestroyImmediate(Object obj, Boolean allowDestroyingAssets) { }
	// RVA: 0x6889284 VA: 0x7598ea1284
	public static Void DestroyImmediate(Object obj) { }
	// RVA: 0x68892fc VA: 0x7598ea12fc
	public static Object[] FindObjectsOfType(Type type) { }
	// RVA: 0x6889374 VA: 0x7598ea1374
	public static Object[] FindObjectsOfType(Type type, Boolean includeInactive) { }
	// RVA: 0x68893b8 VA: 0x7598ea13b8
	public static Object[] FindObjectsByType(Type type, FindObjectsSortMode sortMode) { }
	// RVA: 0x6889440 VA: 0x7598ea1440
	public static Object[] FindObjectsByType(Type type, FindObjectsInactive findObjectsInactive, FindObjectsSortMode sortMode) { }
	// RVA: 0x6889494 VA: 0x7598ea1494
	public static Void DontDestroyOnLoad(Object target) { }
	// RVA: 0x68894d0 VA: 0x7598ea14d0
	public HideFlags get_hideFlags() { }
	// RVA: 0x688950c VA: 0x7598ea150c
	public Void set_hideFlags(HideFlags value) { }
	// RVA: 0x6889550 VA: 0x7598ea1550
	public static Void DestroyObject(Object obj, Single t) { }
	// RVA: 0x68895d4 VA: 0x7598ea15d4
	public static Void DestroyObject(Object obj) { }
	// RVA: 0x688964c VA: 0x7598ea164c
	public static Object[] FindSceneObjectsOfType(Type type) { }
	// RVA: 0x68896a0 VA: 0x7598ea16a0
	public static Object[] FindObjectsOfTypeIncludingAssets(Type type) { }
	// RVA: 0x VA: 0x0
	public static T[] FindObjectsOfType() { }
	// RVA: 0x VA: 0x0
	public static T[] FindObjectsByType(FindObjectsSortMode sortMode) { }
	// RVA: 0x VA: 0x0
	public static T[] FindObjectsOfType(Boolean includeInactive) { }
	// RVA: 0x VA: 0x0
	public static T[] FindObjectsByType(FindObjectsInactive findObjectsInactive, FindObjectsSortMode sortMode) { }
	// RVA: 0x VA: 0x0
	public static T FindObjectOfType() { }
	// RVA: 0x VA: 0x0
	public static T FindObjectOfType(Boolean includeInactive) { }
	// RVA: 0x VA: 0x0
	public static T FindFirstObjectByType() { }
	// RVA: 0x VA: 0x0
	public static T FindAnyObjectByType() { }
	// RVA: 0x VA: 0x0
	public static T FindFirstObjectByType(FindObjectsInactive findObjectsInactive) { }
	// RVA: 0x VA: 0x0
	public static T FindAnyObjectByType(FindObjectsInactive findObjectsInactive) { }
	// RVA: 0x68896dc VA: 0x7598ea16dc
	public static Object[] FindObjectsOfTypeAll(Type type) { }
	// RVA: 0x6888b08 VA: 0x7598ea0b08
	private static Void CheckNullArgument(Object arg, String message) { }
	// RVA: 0x68896e4 VA: 0x7598ea16e4
	public static Object FindObjectOfType(Type type) { }
	// RVA: 0x688977c VA: 0x7598ea177c
	public static Object FindFirstObjectByType(Type type) { }
	// RVA: 0x6889820 VA: 0x7598ea1820
	public static Object FindAnyObjectByType(Type type) { }
	// RVA: 0x68898c4 VA: 0x7598ea18c4
	public static Object FindObjectOfType(Type type, Boolean includeInactive) { }
	// RVA: 0x6889968 VA: 0x7598ea1968
	public static Object FindFirstObjectByType(Type type, FindObjectsInactive findObjectsInactive) { }
	// RVA: 0x6889a18 VA: 0x7598ea1a18
	public static Object FindAnyObjectByType(Type type, FindObjectsInactive findObjectsInactive) { }
	// RVA: 0x6889ac8 VA: 0x7598ea1ac8
	public override String ToString() { }
	// RVA: 0x6888524 VA: 0x7598ea0524
	public static Boolean op_Equality(Object x, Object y) { }
	// RVA: 0x688472c VA: 0x7598e9c72c
	public static Boolean op_Inequality(Object x, Object y) { }
	// RVA: 0x68883f8 VA: 0x7598ea03f8
	private static Int32 GetOffsetOfInstanceIDInCPlusPlusObject() { }
	// RVA: 0x68887a8 VA: 0x7598ea07a8
	private static Boolean CurrentThreadIsMainThread() { }
	// RVA: 0x6888f38 VA: 0x7598ea0f38
	private static Object Internal_CloneSingle(Object data) { }
	// RVA: 0x6889128 VA: 0x7598ea1128
	private static Object Internal_CloneSingleWithParent(Object data, Transform parent, Boolean worldPositionStays) { }
	// RVA: 0x6888b5c VA: 0x7598ea0b5c
	private static Object Internal_InstantiateSingle(Object data, Vector3 pos, Quaternion rot) { }
	// RVA: 0x6888d9c VA: 0x7598ea0d9c
	private static Object Internal_InstantiateSingleWithParent(Object data, Transform parent, Vector3 pos, Quaternion rot) { }
	// RVA: 0x6889b3c VA: 0x7598ea1b3c
	private static String ToString(Object obj) { }
	// RVA: 0x688884c VA: 0x7598ea084c
	private static String GetName(Object obj) { }
	// RVA: 0x6889c28 VA: 0x7598ea1c28
	internal static Boolean IsPersistent(Object obj) { }
	// RVA: 0x688890c VA: 0x7598ea090c
	private static Void SetName(Object obj, String name) { }
	// RVA: 0x6889c64 VA: 0x7598ea1c64
	internal static Boolean DoesObjectWithInstanceIDExist(Int32 instanceID) { }
	// RVA: 0x6889ca0 VA: 0x7598ea1ca0
	internal static Object FindObjectFromInstanceID(Int32 instanceID) { }
	// RVA: 0x6889cdc VA: 0x7598ea1cdc
	internal static Object ForceLoadFromInstanceID(Int32 instanceID) { }
	// RVA: 0x68840b4 VA: 0x7598e9c0b4
	public Void .ctor() { }
	// RVA: 0x6889d18 VA: 0x7598ea1d18
	private static Void .cctor() { }
	// RVA: 0x6889b78 VA: 0x7598ea1b78
	private static Object Internal_InstantiateSingle_Injected(Object data, ref Vector3 pos, ref Quaternion rot) { }
	// RVA: 0x6889bcc VA: 0x7598ea1bcc
	private static Object Internal_InstantiateSingleWithParent_Injected(Object data, Transform parent, ref Vector3 pos, ref Quaternion rot) { }
}
```
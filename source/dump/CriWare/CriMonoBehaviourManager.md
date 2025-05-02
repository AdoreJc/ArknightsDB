# CriMonoBehaviourManager

**Namespace:** `CriWare`


## Methods

- `Boolean Register(CriMonoBehaviour)`

- `Void Awake()`

- `Void Update()`

- `Void LateUpdate()`


## Dump
```C#
// Dll : CriMw.CriWare.Runtime.dll
// Namespace : CriWare
public class CriMonoBehaviourManager : MonoBehaviour
{
	private static CriMonoBehaviourManager _instance; // 0x0
	private static List`1 criMonoBehaviourList; // 0x8

	public static CriMonoBehaviourManager instance { get; }

	// RVA: 0x414d878 VA: 0x7596765878
	public static CriMonoBehaviourManager get_instance() { }
	// RVA: 0x414dc7c VA: 0x7596765c7c
	public static Void CreateInstance() { }
	// RVA: 0x414dd40 VA: 0x7596765d40
	private static Int32 GetIndex(CriMonoBehaviour criMonoBehaviour) { }
	// RVA: 0x414d8d4 VA: 0x75967658d4
	public Boolean Register(CriMonoBehaviour criMonoBehaviour) { }
	// RVA: 0x414daf4 VA: 0x7596765af4
	public static Boolean UnRegister(CriMonoBehaviour criMonoBehaviour) { }
	// RVA: 0x414de38 VA: 0x7596765e38
	private Void Awake() { }
	// RVA: 0x414df28 VA: 0x7596765f28
	private Void Update() { }
	// RVA: 0x414e0d4 VA: 0x75967660d4
	private Void LateUpdate() { }
	// RVA: 0x414e280 VA: 0x7596766280
	public Void .ctor() { }
	// RVA: 0x414e288 VA: 0x7596766288
	private static Void .cctor() { }
}
```
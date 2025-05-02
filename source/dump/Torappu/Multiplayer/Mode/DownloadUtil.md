# DownloadUtil

**Namespace:** `Torappu.Multiplayer.Mode`


## Fields

- `String _url`


## Methods

- `Void Start()`

- `Void OnDestroy()`

- `IEnumerator _DoDownload()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Multiplayer.Mode
public class DownloadUtil : MonoBehaviour
{
	private String _url; // 0x18
	private Action`2 _complete; // 0x20


	// RVA: 0x35aa864 VA: 0x7595bc2864
	public static Void DownloadFile(String url, Action`2 complete) { }
	// RVA: 0x35aac44 VA: 0x7595bc2c44
	private Void Start() { }
	// RVA: 0x35aacfc VA: 0x7595bc2cfc
	private Void OnDestroy() { }
	// RVA: 0x35aac88 VA: 0x7595bc2c88
	private IEnumerator _DoDownload() { }
	// RVA: 0x35aad48 VA: 0x7595bc2d48
	public Void .ctor() { }
}
```
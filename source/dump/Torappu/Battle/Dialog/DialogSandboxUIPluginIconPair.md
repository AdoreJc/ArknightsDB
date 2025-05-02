# DialogSandboxUIPluginIconPair

**Namespace:** `Torappu.Battle.Dialog`


## Fields

- `Text _iconVal`

- `Image _image`

- `Int32 m_lastVal`

- `String m_itemId`


## Methods

- `Void Render(String)`

- `Void _UpdateVal()`

- `Void Update()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle.Dialog
public class DialogSandboxUIPluginIconPair : MonoBehaviour, IHotfixable
{
	private Text _iconVal; // 0x18
	private Image _image; // 0x20
	private Int32 m_lastVal; // 0x28
	private String m_itemId; // 0x30
	private static DelegateBridge __Hotfix0_Render; // 0x0
	private static DelegateBridge __Hotfix0__UpdateVal; // 0x8
	private static DelegateBridge __Hotfix0_Update; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18


	// RVA: 0x1d2bd38 VA: 0x7594343d38
	public Void Render(String itemId) { }
	// RVA: 0x1d2bfd4 VA: 0x7594343fd4
	private Void _UpdateVal() { }
	// RVA: 0x1d2c0dc VA: 0x75943440dc
	private Void Update() { }
	// RVA: 0x1d2c144 VA: 0x7594344144
	public Void .ctor() { }
}
```
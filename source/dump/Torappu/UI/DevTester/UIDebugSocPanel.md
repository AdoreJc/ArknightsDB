# UIDebugSocPanel

**Namespace:** `Torappu.UI.DevTester`


## Fields

- `Text _platform`

- `Text _isSimulator`

- `Text _soc`

- `Text _processor`


## Methods

- `String _GetPlatform()`

- `String _GetProcessor()`

- `String _GetIsSimulator()`

- `String _GetSoc()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.DevTester
public class UIDebugSocPanel : MonoBehaviour
{
	private Text _platform; // 0x18
	private Text _isSimulator; // 0x20
	private Text _soc; // 0x28
	private Text _processor; // 0x30


	// RVA: 0x29bb340 VA: 0x7594fd3340
	private String _GetPlatform() { }
	// RVA: 0x29bb3d0 VA: 0x7594fd33d0
	private String _GetProcessor() { }
	// RVA: 0x29bb424 VA: 0x7594fd3424
	private String _GetIsSimulator() { }
	// RVA: 0x29bb4c8 VA: 0x7594fd34c8
	private String _GetSoc() { }
	// RVA: 0x29bb51c VA: 0x7594fd351c
	public Void .ctor() { }
}
```
# UIAudioPreloader

**Namespace:** `Torappu.Audio`


## Fields

- `Boolean _preloadInternalSounds`

- `Boolean _preloadBuildingSounds`


## Methods

- `Void Start()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Audio
public class UIAudioPreloader : MonoBehaviour, IHotfixable
{
	private Boolean _preloadInternalSounds; // 0x18
	private Boolean _preloadBuildingSounds; // 0x19
	private String[] _extraSignals; // 0x20
	private static DelegateBridge __Hotfix0_Start; // 0x0
	private static DelegateBridge _c__Hotfix0_ctor; // 0x8


	// RVA: 0x3eba5f8 VA: 0x75964d25f8
	private Void Start() { }
	// RVA: 0x3eba9f0 VA: 0x75964d29f0
	public Void .ctor() { }
}
```
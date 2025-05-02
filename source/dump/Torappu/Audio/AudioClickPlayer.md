# AudioClickPlayer

**Namespace:** `Torappu.Audio`


## Fields

- `AudioSoundType _soundType`

- `UiInternalSoundType _internalType`

- `UiBuildingSoundType _buildingSoundType`

- `String _signal`

- `String _subsignal`


## Methods

- `Boolean _ShowCustomFields()`

- `Boolean _ShowInternalFields()`

- `Boolean _ShowBuildingSoundFields()`

- `Void _OnTargetButtonClicked()`

- `Void OnPointerDown(PointerEventData)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Audio
public class AudioClickPlayer : MonoBehaviour, IPointerDownHandler, IEventSystemHandler, IHotfixable
{
	private AudioSoundType _soundType; // 0x18
	private UiInternalSoundType _internalType; // 0x1c
	private UiBuildingSoundType _buildingSoundType; // 0x20
	private String _signal; // 0x28
	private String _subsignal; // 0x30
	private static DelegateBridge __Hotfix0__ShowCustomFields; // 0x0
	private static DelegateBridge __Hotfix0__ShowInternalFields; // 0x8
	private static DelegateBridge __Hotfix0__ShowBuildingSoundFields; // 0x10
	private static DelegateBridge __Hotfix0__OnTargetButtonClicked; // 0x18
	private static DelegateBridge __Hotfix0_OnPointerDown; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x28


	// RVA: 0x3eb6e70 VA: 0x75964cee70
	private Boolean _ShowCustomFields() { }
	// RVA: 0x3eb6ee0 VA: 0x75964ceee0
	private Boolean _ShowInternalFields() { }
	// RVA: 0x3eb6f50 VA: 0x75964cef50
	private Boolean _ShowBuildingSoundFields() { }
	// RVA: 0x3eb6fc0 VA: 0x75964cefc0
	private Void _OnTargetButtonClicked() { }
	// RVA: 0x3eb716c VA: 0x75964cf16c
	public Void OnPointerDown(PointerEventData eventData) { }
	// RVA: 0x3eb71e8 VA: 0x75964cf1e8
	public Void .ctor() { }
}
```
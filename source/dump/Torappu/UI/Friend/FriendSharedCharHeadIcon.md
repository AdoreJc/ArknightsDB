# FriendSharedCharHeadIcon

**Namespace:** `Torappu.UI.Friend`


## Fields

- `Image _headIcon`

- `Image _eliteSprite`

- `GameObject _specMaxPart`

- `Text _level`

- `TwoStateToggle _emptyToggle`


## Methods

- `Void ApplyNullableData(SharedCharData)`

- `Void ApplyNullableData(Int32)`

- `Void ApplyNullableData(PlayerCharacter)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Friend
public class FriendSharedCharHeadIcon : MonoBehaviour, IHotfixable
{
	private Image _headIcon; // 0x18
	private Image _eliteSprite; // 0x20
	private GameObject _specMaxPart; // 0x28
	private Text _level; // 0x30
	private TwoStateToggle _emptyToggle; // 0x38
	private static DelegateBridge __Hotfix0_ApplyNullableData; // 0x0
	private static DelegateBridge __Hotfix1_ApplyNullableData; // 0x8
	private static DelegateBridge __Hotfix2_ApplyNullableData; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18


	// RVA: 0x28cd534 VA: 0x7594ee5534
	public Void ApplyNullableData(SharedCharData charData) { }
	// RVA: 0x28d022c VA: 0x7594ee822c
	public Void ApplyNullableData(Int32 charInstId) { }
	// RVA: 0x28d0330 VA: 0x7594ee8330
	public Void ApplyNullableData(PlayerCharacter charData) { }
	// RVA: 0x28d0548 VA: 0x7594ee8548
	public Void .ctor() { }
}
```
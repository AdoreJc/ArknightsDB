# SocialGetHeadIconView

**Namespace:** `Torappu.UI.Shop`


## Fields

- `Image _headIcon`

- `Image _eliteSprite`

- `Text _level`

- `GameObject _ablePart`

- `GameObject _notAblePart`

- `Text _usedTimesText`


## Methods

- `Void ApplyData(String, Int32)`

- `Void ApplyEmpty()`

- `Void ApplyData(PlayerCharacter)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Shop
public class SocialGetHeadIconView : MonoBehaviour
{
	private Image _headIcon; // 0x18
	private Image _eliteSprite; // 0x20
	private Text _level; // 0x28
	private GameObject _ablePart; // 0x30
	private GameObject _notAblePart; // 0x38
	private Text _usedTimesText; // 0x40


	// RVA: 0x246f950 VA: 0x7594a87950
	public Void ApplyData(String charId, Int32 usedTimes) { }
	// RVA: 0x246fa48 VA: 0x7594a87a48
	public Void ApplyEmpty() { }
	// RVA: 0x246fb78 VA: 0x7594a87b78
	public Void ApplyData(PlayerCharacter charData) { }
	// RVA: 0x246fce4 VA: 0x7594a87ce4
	public Void .ctor() { }
}
```
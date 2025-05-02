# GachaDemo

**Namespace:** `Torappu.Gacha`


## Fields

- `PlayMode _playMode`

- `GachaConfig _one`


## Methods

- `Void _PlayOne()`

- `Void _PlayTen()`

- `Input _CreateInput(GachaConfig)`

- `Void OnGUI()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Gacha
public class GachaDemo : MonoBehaviour
{
	private PlayMode _playMode; // 0x18
	private GachaConfig _one; // 0x20
	private GachaConfig[] _ten; // 0x30


	// RVA: 0x35c539c VA: 0x7595bdd39c
	private Void _PlayOne() { }
	// RVA: 0x35c568c VA: 0x7595bdd68c
	private Void _PlayTen() { }
	// RVA: 0x35c5504 VA: 0x7595bdd504
	private Input _CreateInput(GachaConfig config) { }
	// RVA: 0x35c590c VA: 0x7595bdd90c
	private Void OnGUI() { }
	// RVA: 0x35c5a24 VA: 0x7595bdda24
	public Void .ctor() { }
}
```
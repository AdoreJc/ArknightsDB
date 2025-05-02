# EnemyDuelEmojiData

**Namespace:** `Torappu.UI.EnemyDuel.Service`


## Fields

- `String id`

- `String emojiGroup`

- `String emojiId`


## Methods

- `Void Read(IStreamReader)`

- `Void OnAllocate()`

- `Void OnRecycle()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.EnemyDuel.Service
public class EnemyDuelEmojiData : IReusable
{
	public String id; // 0x10
	public String emojiGroup; // 0x18
	public String emojiId; // 0x20


	// RVA: 0x29aa274 VA: 0x7594fc2274
	public Void Read(IStreamReader from) { }
	// RVA: 0x29aa400 VA: 0x7594fc2400
	public Void OnAllocate() { }
	// RVA: 0x29aa404 VA: 0x7594fc2404
	public Void OnRecycle() { }
	// RVA: 0x29a738c VA: 0x7594fbf38c
	public Void .ctor() { }
}
```
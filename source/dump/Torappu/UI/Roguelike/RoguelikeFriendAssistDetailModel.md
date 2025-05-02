# RoguelikeFriendAssistDetailModel

**Namespace:** `Torappu.UI.Roguelike`


## Fields

- `String m_ticketIndex`

- `ProfessionCategory m_profession`

- `FriendAssistData m_friendAssistData`


## Properties

- `FriendAssistData friendAssistData`

- `String ticketIndex`

- `String profession`

- `String assistUid`

- `SharedCharData assistCharData`


## Methods

- `FriendAssistData get_friendAssistData()`

- `String get_ticketIndex()`

- `String get_profession()`

- `String get_assistUid()`

- `SharedCharData get_assistCharData()`

- `Void LoadData(String, ProfessionCategory, FriendAssistData)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Roguelike
public class RoguelikeFriendAssistDetailModel
{
	private String m_ticketIndex; // 0x10
	private ProfessionCategory m_profession; // 0x18
	private FriendAssistData m_friendAssistData; // 0x20

	public FriendAssistData friendAssistData { get; }
	public String ticketIndex { get; }
	public String profession { get; }
	public String assistUid { get; }
	public SharedCharData assistCharData { get; }

	// RVA: 0x2a3811c VA: 0x759505011c
	public FriendAssistData get_friendAssistData() { }
	// RVA: 0x2a38124 VA: 0x7595050124
	public String get_ticketIndex() { }
	// RVA: 0x2a370d0 VA: 0x759504f0d0
	public String get_profession() { }
	// RVA: 0x2a37138 VA: 0x759504f138
	public String get_assistUid() { }
	// RVA: 0x2a3715c VA: 0x759504f15c
	public SharedCharData get_assistCharData() { }
	// RVA: 0x2a3812c VA: 0x759505012c
	public Void LoadData(String recruitIndex, ProfessionCategory profession, FriendAssistData assistData) { }
	// RVA: 0x2a38164 VA: 0x7595050164
	public Void .ctor() { }
}
```
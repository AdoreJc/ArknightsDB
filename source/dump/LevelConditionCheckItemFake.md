# LevelConditionCheckItemFake

**Namespace:** ` `


## Fields

- `Int32 fakeLevel`

- `RoomType fakeRoomType`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
private class LevelConditionCheckItemFake : LevelConditionCheckItem
{
	public Int32 fakeLevel; // 0x10
	public RoomType fakeRoomType; // 0x14

	public override Int32 level { get; }
	public override RoomType roomType { get; }

	// RVA: 0x3d56c30 VA: 0x759636ec30
	public override Int32 get_level() { }
	// RVA: 0x3d56c38 VA: 0x759636ec38
	public override RoomType get_roomType() { }
	// RVA: 0x3d56bb4 VA: 0x759636ebb4
	public Void .ctor() { }
}
```
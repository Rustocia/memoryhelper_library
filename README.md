How To Use This Library

#1 Create A uintptr_t, EX: uintptr_t GameObjectManager;




#2 GameObjectManager = MemoryHelper::PatternScan(sigs::GameObject);





#3 Create A Sigs Namespace 




namespace sigs
{
	const char* GameObject = "E9 ? ? ? ? CC CC CC CC CC CC CC CC CC CC CC C2 00 00";
}

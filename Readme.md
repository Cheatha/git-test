# Zurückspielen eigener Änderungen
Das Repository enthält eine Software in Version v1.0. Auf diese wende ich meine Änderungen an (zwei commits).
Dann wird die Software auf v1.1 aktualisiert. Ich möchte die Updates »mitnehmen«, aber meine Änderungen aus den beiden commits wiederherstellen.
Mit `git cherry-pick 1ec2a914780aa4b54655ad5e0a96edaa18771bc8` und `git cherry-pick bc449833e7b86199968b7d2c304b1f32fb6c6d88` scheint es geklappt zu haben: In den geänderten Files sind sowohl die Bugfixes als auch meine Änderungen enthalten.

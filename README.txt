winecx build for bottles flatpak usage, fetched directly from https://media.codeweavers.com/pub/crossover/source/ and builded automatically with github action

provided as-is with no commitment, since this is only explanatory project (primarily for testing microsoft office under bottles flatpak), so no testing before release, no constant update, and no support, i'll try my best to give you version specific build if you want to

you just download the archive and extract to bottles flatpak runner directory, like this for example (just follow the versioning or rename it yourself if you want add multiple runner)

mkdir -p ~/.var/app/com.usebottles.bottles/data/bottles/runners/winecx-crossover-24.0.7-jammy
curl -L https://github.com/arfshl/winecx-bottles/releases/download/winecx-24.0.7-jammy/winecx-crossover-24.0.7-jammy.tar.xz --output /tmp/winecx.tar.xz
tar -xJf /tmp/winecx.tar.xz -C ~/.var/app/com.usebottles.bottles/data/bottles/runners/winecx-crossover-24.0.7-jammy
rm /tmp/winecx.tar.xz

crossover changelog: https://www.codeweavers.com/crossover/changelog
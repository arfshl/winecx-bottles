crossover winecx builds fetched directly from https://media.codeweavers.com/pub/crossover/source/ and builded automatically with github action

provided as-is with no commitment, since this is only explanatory project (primarily for testing microsoft office under bottles flatpak), so no testing before release, no constant update, and no support, i'll try my best to give you version specific build if you want to

for example you just download the archive and extract to bottles flatpak runner directory, like this for example (just follow the versioning or rename it yourself if you want add multiple runner)

mkdir -p ~/.var/app/com.usebottles.bottles/data/bottles/runners/winecx-crossover-26.3.0-32bitonly
curl -L https://github.com/arfshl/winecx-builds/releases/download/winecx-26.3.0-jammy/winecx-crossover-26.3.0-32bitonly.tar.xz --output /tmp/winecx.tar.xz
tar -xJf /tmp/winecx.tar.xz -C ~/.var/app/com.usebottles.bottles/data/bottles/runners/winecx-crossover-26.3.0-32bitonly
rm /tmp/winecx.tar.xz

crossover changelog: https://www.codeweavers.com/crossover/changelog
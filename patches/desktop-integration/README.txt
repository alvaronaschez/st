cd ../..
cp patches/desktop-integration/st.png .
cp patches/desktop-integration/st.desktop ~/.local/share/applications
git apply --3way patches/desktop-integration/st-netwmicon-0.8.5-v2.diff
sudo make clean install


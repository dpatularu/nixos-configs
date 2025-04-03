# Disko installation
`sudo nix --experimental-features "nix-command flakes" run github:nix-community/disko/latest -- --mode destroy,format,mount /tmp/disk-config.nix`

#Generate NixOS config
`nixos-generate-config --root /mnt`

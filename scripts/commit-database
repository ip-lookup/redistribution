#!/bin/bash

database_name=$1

echo "Writing commit for database ${database_name}..."
echo "=========="

git add maxmind/${database_name}.zip maxmind/${database_name}.zip.sha256
git status
git diff --staged

git config user.name "github-actions[bot]"
git config user.email "41898282+github-actions[bot]@users.noreply.github.com"
git commit -m "chore: update MaxMind ${database_name} database" --no-verify
stat=$?
if [ $stat -ne 0 ]; then
	exit 1
fi

echo "=========="
echo "Commit written"
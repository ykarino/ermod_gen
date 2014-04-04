ermod script file
========================

gen_structure : log, psf ファイルから soln, refs ディレクトリを作成
gen_input     : log, dcd ファイルから MDinfo, paramaters_er 等を編集

ファイルのダウンロード
----------------------

    git clone git@github.com:ykarino/ermod_gen.git

使い方
--------------------
ヘルプ

    gen_structure --help
	gen_input --help

soln, refs 作成

    gen_structure -l logfile.log -t psffile.psf

parameters_er 作成

    gen_input -l ../logfile.log -x ../dcdfile.dcd


詳しくはermodページ
